# Server Metrics 2026-03-15 11:46:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 48747.9 (13h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1315046
telemt_connections_bad_total 79423
telemt_handshake_timeouts_total 10890
telemt_upstream_connect_attempt_total 9847
telemt_upstream_connect_success_total 9802
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 9847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4563
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 10037
telemt_me_reconnect_success_total 7338
telemt_me_reader_eof_total 7816
telemt_me_idle_close_by_peer_total 7816
telemt_me_route_drop_no_conn_total 435142
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1100753
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4220
telemt_desync_full_logged_total 1193
telemt_desync_suppressed_total 3027
telemt_desync_frames_bucket_total{bucket="1_2"} 1015
telemt_desync_frames_bucket_total{bucket="3_10"} 1657
telemt_desync_frames_bucket_total{bucket="gt_10"} 1548
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7531
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 7327
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 193
telemt_user_connections_total{user="hello"} 1100538
telemt_user_connections_current{user="hello"} 2206
telemt_user_octets_from_client{user="hello"} 15342991968 (14.29 GB)
telemt_user_octets_to_client{user="hello"} 443025977108 (412.60 GB)
telemt_user_unique_ips_current{user="hello"} 628
telemt_user_unique_ips_recent_window{user="hello"} 276
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 48748.6 (13h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 513557
telemt_connections_bad_total 27256
telemt_handshake_timeouts_total 24422
telemt_upstream_connect_attempt_total 12746
telemt_upstream_connect_success_total 12681
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 12746
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5712
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 9956
telemt_me_reconnect_success_total 9891
telemt_me_reader_eof_total 10457
telemt_me_idle_close_by_peer_total 10457
telemt_me_route_drop_no_conn_total 131639
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 404875
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1524
telemt_desync_full_logged_total 521
telemt_desync_suppressed_total 1003
telemt_desync_frames_bucket_total{bucket="1_2"} 565
telemt_desync_frames_bucket_total{bucket="3_10"} 562
telemt_desync_frames_bucket_total{bucket="gt_10"} 397
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 9998
telemt_me_writer_restored_same_endpoint_total 9879
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 405145
telemt_user_connections_current{user="hello"} 731
telemt_user_octets_from_client{user="hello"} 5854709151 (5.45 GB)
telemt_user_octets_to_client{user="hello"} 151675425180 (141.26 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 48748.4 (13h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1003950
telemt_connections_bad_total 33372
telemt_handshake_timeouts_total 101755
telemt_upstream_connect_attempt_total 10826
telemt_upstream_connect_success_total 10773
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 10826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5153
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_reconnect_attempts_total 8673
telemt_me_reconnect_success_total 8298
telemt_me_reader_eof_total 8778
telemt_me_idle_close_by_peer_total 8778
telemt_me_route_drop_no_conn_total 285342
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 703487
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1768
telemt_desync_full_logged_total 622
telemt_desync_suppressed_total 1146
telemt_desync_frames_bucket_total{bucket="1_2"} 397
telemt_desync_frames_bucket_total{bucket="3_10"} 659
telemt_desync_frames_bucket_total{bucket="gt_10"} 712
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 8417
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 8279
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 702010
telemt_user_connections_current{user="hello"} 1261
telemt_user_octets_from_client{user="hello"} 10374536192 (9.66 GB)
telemt_user_octets_to_client{user="hello"} 271808371088 (253.14 GB)
telemt_user_unique_ips_current{user="hello"} 368
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 48748.4 (13h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 521319
telemt_connections_bad_total 63861
telemt_handshake_timeouts_total 27635
telemt_upstream_connect_attempt_total 14332
telemt_upstream_connect_success_total 13960
telemt_upstream_connect_fail_total 372
telemt_upstream_connect_attempts_per_request{bucket="1"} 14332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7304
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 372
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 36132
telemt_me_reconnect_success_total 11494
telemt_me_reader_eof_total 12599
telemt_me_idle_close_by_peer_total 12599
telemt_me_seq_mismatch_total 18
telemt_me_route_drop_no_conn_total 146737
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 390253
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1033
telemt_desync_full_logged_total 260
telemt_desync_suppressed_total 773
telemt_desync_frames_bucket_total{bucket="1_2"} 268
telemt_desync_frames_bucket_total{bucket="3_10"} 425
telemt_desync_frames_bucket_total{bucket="gt_10"} 340
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12374
telemt_me_refill_failed_total 770
telemt_me_writer_restored_same_endpoint_total 11462
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 880
telemt_user_connections_total{user="hello"} 390151
telemt_user_connections_current{user="hello"} 573
telemt_user_octets_from_client{user="hello"} 4752405652 (4.43 GB)
telemt_user_octets_to_client{user="hello"} 125025402232 (116.44 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 48749.4 (13h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 548978
telemt_connections_bad_total 6571
telemt_handshake_timeouts_total 11933
telemt_upstream_connect_attempt_total 10852
telemt_upstream_connect_success_total 10797
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 10852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5858
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 8386
telemt_me_reconnect_success_total 8340
telemt_me_reader_eof_total 8860
telemt_me_idle_close_by_peer_total 8860
telemt_me_route_drop_no_conn_total 140792
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 452749
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1769
telemt_desync_full_logged_total 580
telemt_desync_suppressed_total 1189
telemt_desync_frames_bucket_total{bucket="1_2"} 506
telemt_desync_frames_bucket_total{bucket="3_10"} 719
telemt_desync_frames_bucket_total{bucket="gt_10"} 544
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8434
telemt_me_writer_restored_same_endpoint_total 8332
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 452783
telemt_user_connections_current{user="hello"} 859
telemt_user_octets_from_client{user="hello"} 6021221616 (5.61 GB)
telemt_user_octets_to_client{user="hello"} 163627601932 (152.39 GB)
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 123
```