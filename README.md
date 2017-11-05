# vagrant-golang

Vagrantfile to take and run Go projects with. It assumes that the `Vagrantfile` is in the root of a Go project, and the Go project is located in a valid GOPATH.

For example this repository is cloned into `$GOPATH/src/github.com/brancz/vagrant-golang`. Then after running

```bash
vagrant up
```

it ensures, that the project is also correctly located at `/home/ubuntu/go/src/github.com/brancz/vagrant-golang` inside of the virtual machine.
