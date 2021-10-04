# C8-Vue-JS-Course
Vue.js crash course - https://www.youtube.com/watch?v=4deVCNJq3qc&amp;feature=youtu.be


Bootstrap a Vue based project with TypeScript support. Reference - https://cli.vuejs.org/


Setup appropriate linting and style formatting. (should be part of vue-cli)


Setup Skylab SDK - https://skylabsdk.avalara.io/ (Use artifactory - get access to Artificatory for local access and setup for builds based on hercule-public)


Build a standalone UI for Taxability Matrix support. Present taxability information for US/Canada. API Reference - http://hercule-api.midgard.avalara.io/api/swagger#/taxability


The UI should use query params to create a "shareable" link to the taxability matrix with the list of taxcodes and jurisdictions selected. (Hint: Use Vue Router and props appropriately)


Add appropriate Unit tests and functional tests for the UI. Use Taiko or Cypress for functional tests


Setup build pipeline on GoCD. Build pipeline should run lint, format and tests.


Containerize the application and deploy to local Kubernetes. (Using minikube or equivalent - https://kubernetes.io/docs/tasks/tools/install-minikube/)
