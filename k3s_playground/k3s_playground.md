This shouldn’t take long...

Start by installing k3s using the following command:

`curl -sfL https://get.k3s.io | sh -`{{execute}}

Check for Ready node, takes maybe 30 seconds:

`k3s kubectl get node`{{execute}}
