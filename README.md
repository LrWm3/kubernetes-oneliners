# kubernetes-oneliners

A collection of k8s oneliners; files that can be used to solve problems while better solutions are investigated.

These k8s resources typically use the command-line and rely on simple unix tools to make it possible to deploy them with most debian-based docker images.

## helpful-chaos-monkey

A deployment which monitors specific kubernetes pods' for deadlocks by inspecting if we have any logs in the last interval of time.

## i-help-you-pull-the-big-image-everywhere

A daemonset which can be used to force cache an image to all nodes. Better to use a pull-through docker registry to cache but works in a pinch.
