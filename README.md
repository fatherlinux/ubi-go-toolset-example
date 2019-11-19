# Preparation for All Examples

Clone this repository:
`git clone https://github.com/fatherlinux/ubi-go-toolset-example.git`

Change directories:
`cd ubi-go-toolset-example`

# Local Example

Build:
`podman build -t hello-world -f Containerfile.local`

Run:
`podman run -it --rm hello-world`

Output:
`hello world`

# Remote Example

Build:
`podman build -t remote-example -f Containerfile.remote`

Run:
`podman run -it --rm remote-example`

Output:
`Usage of gomtree:
  -K string
...`


# Multi-Stage Example

Build:
`podman build -t hello-world-multi -f Containerfile.remote`

Run:
`podman run -it --rm hello-world-multi`

Output:
`hello world`
