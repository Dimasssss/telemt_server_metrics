# Server Metrics 2026-03-15 06:45:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 30672.2 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 499913
telemt_connections_bad_total 9818
telemt_handshake_timeouts_total 3434
telemt_upstream_connect_attempt_total 6425
telemt_upstream_connect_success_total 6399
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3016
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 4888
telemt_me_reconnect_success_total 4864
telemt_me_reader_eof_total 5139
telemt_me_idle_close_by_peer_total 5139
telemt_me_route_drop_no_conn_total 153437
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 424593
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1126
telemt_desync_full_logged_total 352
telemt_desync_suppressed_total 774
telemt_desync_frames_bucket_total{bucket="1_2"} 233
telemt_desync_frames_bucket_total{bucket="3_10"} 420
telemt_desync_frames_bucket_total{bucket="gt_10"} 473
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 4919
telemt_me_writer_restored_same_endpoint_total 4853
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 424601
telemt_user_connections_current{user="hello"} 1568
telemt_user_octets_from_client{user="hello"} 4857049488 (4.52 GB)
telemt_user_octets_to_client{user="hello"} 150271627548 (139.95 GB)
telemt_user_unique_ips_current{user="hello"} 469
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 30673.2 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180790
telemt_connections_bad_total 18328
telemt_handshake_timeouts_total 5575
telemt_upstream_connect_attempt_total 8639
telemt_upstream_connect_success_total 8594
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 8639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3874
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 6771
telemt_me_reconnect_success_total 6735
telemt_me_reader_eof_total 7130
telemt_me_idle_close_by_peer_total 7130
telemt_me_route_drop_no_conn_total 45707
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 151533
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 489
telemt_desync_full_logged_total 173
telemt_desync_suppressed_total 316
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 197
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 6763
telemt_me_writer_restored_same_endpoint_total 6727
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 151825
telemt_user_connections_current{user="hello"} 512
telemt_user_octets_from_client{user="hello"} 2507360259 (2.34 GB)
telemt_user_octets_to_client{user="hello"} 55588710912 (51.77 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 30673.3 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331175
telemt_connections_bad_total 9141
telemt_handshake_timeouts_total 30967
telemt_upstream_connect_attempt_total 7076
telemt_upstream_connect_success_total 7044
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3276
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 5521
telemt_me_reconnect_success_total 5492
telemt_me_reader_eof_total 5809
telemt_me_idle_close_by_peer_total 5809
telemt_me_route_drop_no_conn_total 84988
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 276863
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 514
telemt_desync_full_logged_total 221
telemt_desync_suppressed_total 293
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 190
telemt_desync_frames_bucket_total{bucket="gt_10"} 208
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 5552
telemt_me_writer_restored_same_endpoint_total 5473
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 276651
telemt_user_connections_current{user="hello"} 756
telemt_user_octets_from_client{user="hello"} 4317456276 (4.02 GB)
telemt_user_octets_to_client{user="hello"} 115431270596 (107.50 GB)
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 30673.1 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 228526
telemt_connections_bad_total 41476
telemt_handshake_timeouts_total 14702
telemt_upstream_connect_attempt_total 10375
telemt_upstream_connect_success_total 10135
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 10375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5303
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 17159
telemt_me_reconnect_success_total 8605
telemt_me_reader_eof_total 9147
telemt_me_idle_close_by_peer_total 9147
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 54631
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167620
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 275
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 201
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 8945
telemt_me_refill_failed_total 266
telemt_me_writer_restored_same_endpoint_total 8579
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 340
telemt_user_connections_total{user="hello"} 167623
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 1439814212 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 58485111472 (54.47 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 30673.9 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166830
telemt_connections_bad_total 247
telemt_handshake_timeouts_total 1614
telemt_upstream_connect_attempt_total 6869
telemt_upstream_connect_success_total 6841
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 6869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3834
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 5325
telemt_me_reconnect_success_total 5302
telemt_me_reader_eof_total 5655
telemt_me_idle_close_by_peer_total 5655
telemt_me_route_drop_no_conn_total 49123
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156699
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 633
telemt_desync_full_logged_total 208
telemt_desync_suppressed_total 425
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5353
telemt_me_writer_restored_same_endpoint_total 5294
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 156706
telemt_user_connections_current{user="hello"} 604
telemt_user_octets_from_client{user="hello"} 1514705516 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 57016441064 (53.10 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 74
```