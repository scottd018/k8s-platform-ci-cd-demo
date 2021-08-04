test:
	kubectl apply \
		-f ../01-litmus-namespace.yaml \
		-f ../02-litmus-test-rbac.yaml \
		-f ../03-litmus-operator.yaml; \
		sleep 15; \
		kubectl apply -f ../99-litmus-experiments.yaml
