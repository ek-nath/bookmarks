## Projects
### Beyla
- [Github](https://github.com/grafana/beyla)
- eBPF-based auto-instrumentation of HTTP/HTTPS/GRPC Go services, as well as HTTP/HTTPS services written in other languages (intercepting Kernel-level socket operations as well as OpenSSL invocations).

### ebpf_exporter
- [Github](https://github.com/cloudflare/ebpf_exporter)
- Prometheus exporter for custom eBPF metrics.
- Motivation of this exporter is to allow you to write eBPF code and export metrics that are not otherwise accessible from the Linux kernel.

### ssh-probe
- [Github](https://github.com/Gui774ume/ssh-probe)
- ssh-probe helps monitor and protect SSH sessions. Relying on predefined security profiles for each user, ssh-probe introduces a new access control layer that can restrict what a user can do on a server, including the root user. On a technical standpoint, ssh-probe relies on eBPF to collect runtime data on up to 127 hook points in the kernel. When an action diverges from the security profile of a session, ssh-probe relies on its syscall hook points to grant or deny access to specific operations. Access can also be granted through an MFA verification.


## Talks
### Hello eBPF! Goobye Sidecars? - Liz Rice
- [Youtunbe](https://www.youtube.com/watch?v=0JFd0W2CcMw)
