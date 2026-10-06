# orders-api

Order management API

Owner: `group:default/idp-team` - generated from the **Node.js service** golden path.

- `server.js` - the service (`/` and `/health` on port 8080)
- `catalog-info.yaml` - how Developer Hub knows about this component
- `devfile.yaml` - how OpenShift Dev Spaces builds a workspace for it
- `deploy/` - OpenShift manifests (build + run), all labelled `backstage.io/kubernetes-id: orders-api`
