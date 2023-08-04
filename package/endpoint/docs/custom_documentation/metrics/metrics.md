# Endpoint Metrics

- OS: Linux, Windows, macOS
- Data Stream: `metrics-endpoint.metrics-*`
- KQL: `event.action : "endpoint_metrics" and event.dataset : "endpoint.metrics" and event.module : "endpoint"`

This is an internal state management document that includes metrics on Endpoint's performance.


| Field |
|---|
| @timestamp |
| Endpoint.metrics.cpu.endpoint.histogram.counts |
| Endpoint.metrics.cpu.endpoint.histogram.values |
| Endpoint.metrics.cpu.endpoint.latest |
| Endpoint.metrics.cpu.endpoint.mean |
| Endpoint.metrics.disks.device |
| Endpoint.metrics.disks.endpoint_drive |
| Endpoint.metrics.disks.free |
| Endpoint.metrics.disks.fstype |
| Endpoint.metrics.disks.mount |
| Endpoint.metrics.disks.total |
| Endpoint.metrics.documents_volume.alerts.sent_bytes |
| Endpoint.metrics.documents_volume.alerts.sent_count |
| Endpoint.metrics.documents_volume.alerts.suppressed_bytes |
| Endpoint.metrics.documents_volume.alerts.suppressed_count |
| Endpoint.metrics.documents_volume.api_events.sent_bytes |
| Endpoint.metrics.documents_volume.api_events.sent_count |
| Endpoint.metrics.documents_volume.api_events.sources.sent_bytes |
| Endpoint.metrics.documents_volume.api_events.sources.sent_count |
| Endpoint.metrics.documents_volume.api_events.sources.source |
| Endpoint.metrics.documents_volume.api_events.sources.suppressed_bytes |
| Endpoint.metrics.documents_volume.api_events.sources.suppressed_count |
| Endpoint.metrics.documents_volume.api_events.suppressed_bytes |
| Endpoint.metrics.documents_volume.api_events.suppressed_count |
| Endpoint.metrics.documents_volume.diagnostic_alerts.sent_bytes |
| Endpoint.metrics.documents_volume.diagnostic_alerts.sent_count |
| Endpoint.metrics.documents_volume.diagnostic_alerts.suppressed_bytes |
| Endpoint.metrics.documents_volume.diagnostic_alerts.suppressed_count |
| Endpoint.metrics.documents_volume.dns_events.sent_bytes |
| Endpoint.metrics.documents_volume.dns_events.sent_count |
| Endpoint.metrics.documents_volume.dns_events.suppressed_bytes |
| Endpoint.metrics.documents_volume.dns_events.suppressed_count |
| Endpoint.metrics.documents_volume.file_events.sent_bytes |
| Endpoint.metrics.documents_volume.file_events.sent_count |
| Endpoint.metrics.documents_volume.file_events.suppressed_bytes |
| Endpoint.metrics.documents_volume.file_events.suppressed_count |
| Endpoint.metrics.documents_volume.library_events.sent_bytes |
| Endpoint.metrics.documents_volume.library_events.sent_count |
| Endpoint.metrics.documents_volume.library_events.suppressed_bytes |
| Endpoint.metrics.documents_volume.library_events.suppressed_count |
| Endpoint.metrics.documents_volume.network_events.sent_bytes |
| Endpoint.metrics.documents_volume.network_events.sent_count |
| Endpoint.metrics.documents_volume.network_events.suppressed_bytes |
| Endpoint.metrics.documents_volume.network_events.suppressed_count |
| Endpoint.metrics.documents_volume.overall.sent_bytes |
| Endpoint.metrics.documents_volume.overall.sent_count |
| Endpoint.metrics.documents_volume.overall.suppressed_bytes |
| Endpoint.metrics.documents_volume.overall.suppressed_count |
| Endpoint.metrics.documents_volume.process_events.sent_bytes |
| Endpoint.metrics.documents_volume.process_events.sent_count |
| Endpoint.metrics.documents_volume.process_events.suppressed_bytes |
| Endpoint.metrics.documents_volume.process_events.suppressed_count |
| Endpoint.metrics.documents_volume.registry_events.sent_bytes |
| Endpoint.metrics.documents_volume.registry_events.sent_count |
| Endpoint.metrics.documents_volume.registry_events.suppressed_bytes |
| Endpoint.metrics.documents_volume.registry_events.suppressed_count |
| Endpoint.metrics.documents_volume.security_events.sent_bytes |
| Endpoint.metrics.documents_volume.security_events.sent_count |
| Endpoint.metrics.documents_volume.security_events.suppressed_bytes |
| Endpoint.metrics.documents_volume.security_events.suppressed_count |
| Endpoint.metrics.event_filter.active_global_count |
| Endpoint.metrics.event_filter.active_user_count |
| Endpoint.metrics.malicious_behavior_rules.endpoint_uptime_percent |
| Endpoint.metrics.malicious_behavior_rules.id |
| Endpoint.metrics.memory.endpoint.private.latest |
| Endpoint.metrics.memory.endpoint.private.mean |
| Endpoint.metrics.system_impact.authentication_events.week_idle_ms |
| Endpoint.metrics.system_impact.authentication_events.week_ms |
| Endpoint.metrics.system_impact.behavior_protection.week_idle_ms |
| Endpoint.metrics.system_impact.behavior_protection.week_ms |
| Endpoint.metrics.system_impact.cred_access_events.week_idle_ms |
| Endpoint.metrics.system_impact.cred_access_events.week_ms |
| Endpoint.metrics.system_impact.diagnostic_behavior_protection.week_idle_ms |
| Endpoint.metrics.system_impact.diagnostic_behavior_protection.week_ms |
| Endpoint.metrics.system_impact.dns_events.week_idle_ms |
| Endpoint.metrics.system_impact.dns_events.week_ms |
| Endpoint.metrics.system_impact.file_events.week_idle_ms |
| Endpoint.metrics.system_impact.file_events.week_ms |
| Endpoint.metrics.system_impact.library_load_events.week_idle_ms |
| Endpoint.metrics.system_impact.library_load_events.week_ms |
| Endpoint.metrics.system_impact.malware.week_idle_ms |
| Endpoint.metrics.system_impact.malware.week_ms |
| Endpoint.metrics.system_impact.memory_scan.week_idle_ms |
| Endpoint.metrics.system_impact.memory_scan.week_ms |
| Endpoint.metrics.system_impact.network_events.week_idle_ms |
| Endpoint.metrics.system_impact.network_events.week_ms |
| Endpoint.metrics.system_impact.overall.week_idle_ms |
| Endpoint.metrics.system_impact.overall.week_ms |
| Endpoint.metrics.system_impact.process.code_signature.exists |
| Endpoint.metrics.system_impact.process.code_signature.signing_id |
| Endpoint.metrics.system_impact.process.code_signature.status |
| Endpoint.metrics.system_impact.process.code_signature.subject_name |
| Endpoint.metrics.system_impact.process.code_signature.team_id |
| Endpoint.metrics.system_impact.process.code_signature.trusted |
| Endpoint.metrics.system_impact.process.executable |
| Endpoint.metrics.system_impact.process_events.week_idle_ms |
| Endpoint.metrics.system_impact.process_events.week_ms |
| Endpoint.metrics.system_impact.process_injection.week_idle_ms |
| Endpoint.metrics.system_impact.process_injection.week_ms |
| Endpoint.metrics.system_impact.ransomware.week_idle_ms |
| Endpoint.metrics.system_impact.ransomware.week_ms |
| Endpoint.metrics.system_impact.registry_events.week_idle_ms |
| Endpoint.metrics.system_impact.registry_events.week_ms |
| Endpoint.metrics.system_impact.threat_intelligence_events.week_idle_ms |
| Endpoint.metrics.system_impact.threat_intelligence_events.week_ms |
| Endpoint.metrics.threads.cpu.mean |
| Endpoint.metrics.threads.name |
| Endpoint.metrics.uptime.endpoint |
| Endpoint.metrics.uptime.system |
| agent.build.original |
| agent.id |
| agent.type |
| agent.version |
| data_stream.dataset |
| data_stream.namespace |
| data_stream.type |
| ecs.version |
| elastic.agent.id |
| event.action |
| event.category |
| event.created |
| event.dataset |
| event.id |
| event.kind |
| event.module |
| event.sequence |
| event.type |
| host.architecture |
| host.hostname |
| host.id |
| host.ip |
| host.mac |
| host.name |
| host.os.Ext.variant |
| host.os.family |
| host.os.full |
| host.os.kernel |
| host.os.name |
| host.os.platform |
| host.os.type |
| host.os.version |
| message |
