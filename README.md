# Server Metrics 2026-03-12 03:16:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 19887.7 (5h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169273
telemt_connections_bad_total 1354
telemt_handshake_timeouts_total 3331
telemt_upstream_connect_attempt_total 4568
telemt_upstream_connect_success_total 4568
telemt_upstream_connect_attempts_per_request{bucket="1"} 4568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2148
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 3555
telemt_me_reconnect_success_total 3540
telemt_me_reader_eof_total 3737
telemt_me_idle_close_by_peer_total 3737
telemt_me_route_drop_no_conn_total 61399
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159727
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 332
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 246
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 114
telemt_desync_frames_bucket_total{bucket="gt_10"} 102
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3579
telemt_me_writer_restored_same_endpoint_total 3524
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 159539
telemt_user_connections_current{user="hello"} 525
telemt_user_octets_from_client{user="hello"} 1228201400 (1.14 GB)
telemt_user_octets_to_client{user="hello"} 50116532776 (46.67 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 19888.5 (5h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56289
telemt_connections_bad_total 125
telemt_handshake_timeouts_total 946
telemt_upstream_connect_attempt_total 5671
telemt_upstream_connect_success_total 5668
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 5671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2837
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 4469
telemt_me_reconnect_success_total 4440
telemt_me_reader_eof_total 4706
telemt_me_idle_close_by_peer_total 4706
telemt_me_route_drop_no_conn_total 15586
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52589
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 96
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 47
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4473
telemt_me_writer_restored_same_endpoint_total 4431
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 52768
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 883291483 (842.37 MB)
telemt_user_octets_to_client{user="hello"} 18732452418 (17.45 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 19888.3 (5h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 306087
telemt_connections_bad_total 1526
telemt_handshake_timeouts_total 17422
telemt_upstream_connect_attempt_total 6029
telemt_upstream_connect_success_total 6027
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2575
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 4689
telemt_me_reconnect_success_total 4635
telemt_me_reader_eof_total 4809
telemt_me_idle_close_by_peer_total 4809
telemt_me_route_drop_no_conn_total 30252
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97889
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 243
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 161
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4595
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 4594
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 98218
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 842222352 (803.21 MB)
telemt_user_octets_to_client{user="hello"} 30003869817 (27.94 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 19888.7 (5h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88866
telemt_connections_bad_total 165
telemt_handshake_timeouts_total 4206
telemt_upstream_connect_attempt_total 5952
telemt_upstream_connect_success_total 5924
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 5952
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2576
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 84
telemt_me_reconnect_attempts_total 4914
telemt_me_reconnect_success_total 4896
telemt_me_reader_eof_total 5181
telemt_me_idle_close_by_peer_total 5181
telemt_me_route_drop_no_conn_total 30111
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83307
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 134
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4927
telemt_me_writer_restored_same_endpoint_total 4875
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 83293
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 551562944 (526.01 MB)
telemt_user_octets_to_client{user="hello"} 19917439384 (18.55 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 19888.5 (5h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106893
telemt_connections_bad_total 70
telemt_handshake_timeouts_total 682
telemt_upstream_connect_attempt_total 7328
telemt_upstream_connect_success_total 7252
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 7328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3550
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 109
telemt_me_reconnect_attempts_total 7715
telemt_me_reconnect_success_total 6217
telemt_me_reader_eof_total 6459
telemt_me_idle_close_by_peer_total 6459
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 27746
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 101913
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 352
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 230
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 145
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 6309
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 6201
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 101890
telemt_user_connections_current{user="hello"} 266
telemt_user_octets_from_client{user="hello"} 616711108 (588.14 MB)
telemt_user_octets_to_client{user="hello"} 22260181896 (20.73 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 43
```