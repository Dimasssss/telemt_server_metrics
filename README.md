# Server Metrics 2026-03-11 23:01:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 4588.8 (1h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43411
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 168
telemt_upstream_connect_attempt_total 1037
telemt_upstream_connect_success_total 1037
telemt_upstream_connect_attempts_per_request{bucket="1"} 1037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 472
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 768
telemt_me_reconnect_success_total 766
telemt_me_reader_eof_total 785
telemt_me_idle_close_by_peer_total 785
telemt_me_route_drop_no_conn_total 16010
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40699
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 778
telemt_me_writer_restored_same_endpoint_total 750
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 40683
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 252219116 (240.53 MB)
telemt_user_octets_to_client{user="hello"} 10880921620 (10.13 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 4589.4 (1h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16157
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 167
telemt_upstream_connect_attempt_total 1306
telemt_upstream_connect_success_total 1306
telemt_upstream_connect_attempts_per_request{bucket="1"} 1306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 673
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 1021
telemt_me_reconnect_success_total 1013
telemt_me_reader_eof_total 1041
telemt_me_idle_close_by_peer_total 1041
telemt_me_route_drop_no_conn_total 4244
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15410
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 23
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1017
telemt_me_writer_restored_same_endpoint_total 1004
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 15408
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 504909272 (481.52 MB)
telemt_user_octets_to_client{user="hello"} 7625060028 (7.10 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 4589.2 (1h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37512
telemt_connections_bad_total 284
telemt_handshake_timeouts_total 3447
telemt_upstream_connect_attempt_total 1836
telemt_upstream_connect_success_total 1836
telemt_upstream_connect_attempts_per_request{bucket="1"} 1836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 695
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 1231
telemt_me_reconnect_success_total 1192
telemt_me_reader_eof_total 1139
telemt_me_idle_close_by_peer_total 1139
telemt_me_route_drop_no_conn_total 7014
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25797
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1111
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 1151
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 26151
telemt_user_connections_current{user="hello"} 275
telemt_user_octets_from_client{user="hello"} 207349616 (197.74 MB)
telemt_user_octets_to_client{user="hello"} 12597691033 (11.73 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 4589.6 (1h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24380
telemt_connections_bad_total 60
telemt_handshake_timeouts_total 311
telemt_upstream_connect_attempt_total 1488
telemt_upstream_connect_success_total 1479
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 594
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 1202
telemt_me_reconnect_success_total 1196
telemt_me_reader_eof_total 1206
telemt_me_idle_close_by_peer_total 1206
telemt_me_route_drop_no_conn_total 6581
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23662
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1202
telemt_me_writer_restored_same_endpoint_total 1175
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 23662
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 137012816 (130.67 MB)
telemt_user_octets_to_client{user="hello"} 9768987708 (9.10 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 4589.5 (1h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29451
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 389
telemt_upstream_connect_attempt_total 1957
telemt_upstream_connect_success_total 1939
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 1957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 951
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 1667
telemt_me_reconnect_success_total 1657
telemt_me_reader_eof_total 1633
telemt_me_idle_close_by_peer_total 1633
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 6614
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27788
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 30
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 15
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_me_writer_removed_unexpected_total 1657
telemt_me_writer_restored_same_endpoint_total 1653
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 142
telemt_user_connections_total{user="hello"} 27784
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 185165588 (176.59 MB)
telemt_user_octets_to_client{user="hello"} 7472530240 (6.96 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 32
```