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
- [Article-Monitoring and protecting SSH sessions with eBPF](https://www.sstic.org/media/SSTIC2021/SSTIC-actes/monitoring_and_protecting_ssh_sessions_with_ebpf/SSTIC2021-Article-monitoring_and_protecting_ssh_sessions_with_ebpf-fournier.pdf)

## Talks
### Hello eBPF! Goobye Sidecars? - Liz Rice
- [Youtube](https://www.youtube.com/watch?v=0JFd0W2CcMw)
### Process level network security monitoring & enforcement with eBPF - Guillaume Fournier
- [Article](https://www.sstic.org/media/SSTIC2020/SSTIC-actes/process_level_network_security_monitoring_and_enfo/SSTIC2020-Article-process_level_network_security_monitoring_and_enforcement_with_ebpf-fournier_Cuzi8wu.pdf)
