# k8s-music-stack

k8s specs for Icecast, mpd, ympd, sima - based on https://github.com/vitiMan/docker-music-stack

This class was built for the [Software Freedom School](http://www.SoFree.us), and presented on June 3rd, 2017 at SFS HQ in Denver, Co. 

These containers have been configured to serve everything over 'localhost' -- minikube/alpine/kube-dns continue to have issues resolving internal cluster service names from within pods, so this was the easiest way to make it work.

To get started with this course, open the HTML file in your favorite browser. This is a single-file wiki doc using [tiddlywiki](http://tiddlywiki.com/). Links to tiddlers will open within the file, external links will open in a new tab/window. 

Found a problem? Feel free to submit a PR ;)

*NOTE* there's a bug in VirtualBox (see [this report](https://stackoverflow.com/questions/42294304/minikube-install-in-ubuntu-vm-vt-x-amd-v-enabling-to-vm-inside-another-vm)) - you cannot use nested Virtual Box for this course. You'll have to use KVM, VMware, or some other solution.

Happy kube'ing!


-Mars
