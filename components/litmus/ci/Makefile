test:
	kubectl apply \
		-f components/litmus/01-litmus-namespace.yaml \
		-f components/litmus/02-litmus-test-rbac.yaml \
		-f components/litmus/03-litmus-operator.yaml; \
		sleep 15; \
		kubectl apply -f components/litmus/99-litmus-experiments.yaml
