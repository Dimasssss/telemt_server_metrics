# Server Metrics 2026-03-12 08:12:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 8025.3 (2h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 242554
telemt_connections_bad_total 1314
telemt_handshake_timeouts_total 1821
telemt_upstream_connect_attempt_total 1566
telemt_upstream_connect_success_total 1556
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 696
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 1142
telemt_me_reconnect_success_total 1135
telemt_me_reader_eof_total 1164
telemt_me_idle_close_by_peer_total 1164
telemt_me_route_drop_no_conn_total 81971
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234178
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1160
telemt_desync_full_logged_total 288
telemt_desync_suppressed_total 872
telemt_desync_frames_bucket_total{bucket="1_2"} 285
telemt_desync_frames_bucket_total{bucket="3_10"} 419
telemt_desync_frames_bucket_total{bucket="gt_10"} 456
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1139
telemt_me_writer_restored_same_endpoint_total 1122
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 234095
telemt_user_connections_current{user="hello"} 1294
telemt_user_octets_from_client{user="hello"} 3845639028 (3.58 GB)
telemt_user_octets_to_client{user="hello"} 67602293296 (62.96 GB)
telemt_user_unique_ips_current{user="hello"} 388
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 37645.9 (10h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196087
telemt_connections_bad_total 2618
telemt_handshake_timeouts_total 7232
telemt_upstream_connect_attempt_total 9773
telemt_upstream_connect_success_total 9767
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 9773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4948
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 594
telemt_me_reconnect_attempts_total 7748
telemt_me_reconnect_success_total 7708
telemt_me_reader_eof_total 8183
telemt_me_idle_close_by_peer_total 8183
telemt_me_route_drop_no_conn_total 56858
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171011
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 425
telemt_desync_full_logged_total 169
telemt_desync_suppressed_total 256
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 150
telemt_desync_frames_bucket_total{bucket="gt_10"} 151
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7770
telemt_me_writer_restored_same_endpoint_total 7699
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 171307
telemt_user_connections_current{user="hello"} 487
telemt_user_octets_from_client{user="hello"} 2569137163 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 67840101874 (63.18 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 37645.6 (10h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 578536
telemt_connections_bad_total 2698
telemt_handshake_timeouts_total 43064
telemt_upstream_connect_attempt_total 9885
telemt_upstream_connect_success_total 9880
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 9885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4311
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 506
telemt_me_reconnect_attempts_total 7716
telemt_me_reconnect_success_total 7647
telemt_me_reader_eof_total 8024
telemt_me_idle_close_by_peer_total 8024
telemt_me_route_drop_no_conn_total 111648
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 323647
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1516
telemt_desync_full_logged_total 462
telemt_desync_suppressed_total 1054
telemt_desync_frames_bucket_total{bucket="1_2"} 201
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 792
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 7641
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 7606
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 323925
telemt_user_connections_current{user="hello"} 695
telemt_user_octets_from_client{user="hello"} 3588430020 (3.34 GB)
telemt_user_octets_to_client{user="hello"} 114069722389 (106.24 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 37646.0 (10h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 271106
telemt_connections_bad_total 1795
telemt_handshake_timeouts_total 18457
telemt_upstream_connect_attempt_total 10478
telemt_upstream_connect_success_total 10437
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 10478
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 748
telemt_me_reconnect_attempts_total 8591
telemt_me_reconnect_success_total 8562
telemt_me_reader_eof_total 9091
telemt_me_idle_close_by_peer_total 9091
telemt_me_route_drop_no_conn_total 89816
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 224504
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 402
telemt_desync_full_logged_total 149
telemt_desync_suppressed_total 253
telemt_desync_frames_bucket_total{bucket="1_2"} 135
telemt_desync_frames_bucket_total{bucket="3_10"} 161
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 8616
telemt_me_writer_restored_same_endpoint_total 8541
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 224327
telemt_user_connections_current{user="hello"} 527
telemt_user_octets_from_client{user="hello"} 2576086204 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 77415870248 (72.10 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 37646.1 (10h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 296542
telemt_connections_bad_total 353
telemt_handshake_timeouts_total 2321
telemt_upstream_connect_attempt_total 12555
telemt_upstream_connect_success_total 12408
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 12555
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6393
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5939
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 555
telemt_me_reconnect_attempts_total 12036
telemt_me_reconnect_success_total 10523
telemt_me_reader_eof_total 10959
telemt_me_idle_close_by_peer_total 10959
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 94419
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 279181
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1125
telemt_desync_full_logged_total 381
telemt_desync_suppressed_total 744
telemt_desync_frames_bucket_total{bucket="1_2"} 275
telemt_desync_frames_bucket_total{bucket="3_10"} 410
telemt_desync_frames_bucket_total{bucket="gt_10"} 440
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 10666
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 10502
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 279126
telemt_user_connections_current{user="hello"} 738
telemt_user_octets_from_client{user="hello"} 2831120296 (2.64 GB)
telemt_user_octets_to_client{user="hello"} 67234942040 (62.62 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 107
```