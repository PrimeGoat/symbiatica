# SRAP Educational & Reference Notes

## Core Domains Reviewed
- Remote desktop and application streaming architectures (Citrix HDX, Microsoft RemoteApp, Teradici PCoIP, VMware Blast Extreme).
- Filesystem grafting and namespace virtualization (NTFS reparse points, Windows filter manager, Linux FUSE/eBPF, macOS File Provider, 9P, SMB, NFS).
- GPU surface interception and encoding (DirectComposition, DXGI, Vulkan WSI, Metal, NVENC, AMD AMF, Intel QSV, AV1 encoders).
- Semantic UI diffing frameworks (WPF visual tree, Qt scene graph, Electron DOM diffing, Accessibility APIs).
- Network transport optimization (QUIC, DTLS, RTP/RTCP, adaptive bitrate algorithms such as GCC/SCReAM, forward error correction).
- Security and zero-trust frameworks (NIST SP 800-207, BeyondCorp, mutual TLS practices, hardware roots of trust).
- Enterprise identity standards (OIDC, SAML 2.0, LDAP/Active Directory, SCIM, MFA best practices).
- Compliance regimes (SOC 2, ISO/IEC 27001, FedRAMP, HIPAA, GDPR, FIPS 140-2/3).
- Observability tooling (OpenTelemetry, Prometheus, Grafana, SIEM/SOAR integrations).
- Infrastructure as Code & deployment (Terraform, Ansible, Helm, immutable infrastructure patterns).
- Session recording and audit trails (WORM storage, hash chaining, ledger-based logs).
- Device virtualization (USB/IP, smart card redirection, vGPU/SR-IOV, virtual printing, camera/mic forwarding).
- Resilience engineering (chaos testing, Raft/etcd consensus, active-active clustering, disaster recovery strategies).

## Methodologies & Best Practices Consulted
- Secure Software Development Lifecycle (SSDLC), threat modeling (STRIDE, PASTA), fuzzing and supply-chain security (SLSA, SBOM).
- ITIL/ITSM incident response integration, ServiceNow/Jira workflows.
- DevSecOps deployment pipelines with staged rollouts and automated rollback.
- Accessibility compliance (WCAG 2.2 AA, ARIA practices).
- Data Loss Prevention strategies (content inspection, watermarking, clipboard/file policy enforcement).
- Performance engineering for low-latency interactive streaming (latency budgets, jitter buffers, multi-bitrate ladders).
- Enterprise policy engines (OPA/Rego, XACML) for RBAC/ABAC authoring and evaluation.
- Disaster recovery planning (RTO/RPO definitions, multi-region replication, automated failover drills).
- Chaos engineering frameworks (Chaos Mesh, Gremlin) for failure injection testing.
- Observability-first design with golden signals (latency, traffic, errors, saturation) and SLO-based alerting.

## Additional Considerations
- Emerging trends: AR/VR streaming, volumetric rendering, AI-assisted operations.
- Legal/ethical requirements: consent capture, data subject rights, export controls.
- Multi-tenancy isolation approaches: workload partitioning, namespace isolation, per-tenant encryption keys.
- Collaboration & co-presence use cases: shared control, shadowing, RBAC gating.

These notes capture the educational touchpoints and research anchors used to elevate the specification to a world-class standard under the SRAP methodology.
