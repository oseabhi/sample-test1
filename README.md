name: hellow-world
'on': workflow_dispatch
jobs:
  my-job:
    runs-on: ubuntu-latest
    steps:
      - name: my-step
        run: echo "hellow World!"