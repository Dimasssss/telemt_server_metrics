# Server Metrics 2026-03-12 03:31:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 20806.3 (5h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179818
telemt_connections_bad_total 1354
telemt_handshake_timeouts_total 3362
telemt_upstream_connect_attempt_total 4773
telemt_upstream_connect_success_total 4773
telemt_upstream_connect_attempts_per_request{bucket="1"} 4773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2245
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 3710
telemt_me_reconnect_success_total 3695
telemt_me_reader_eof_total 3900
telemt_me_idle_close_by_peer_total 3900
telemt_me_route_drop_no_conn_total 64982
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169988
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 350
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 258
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 120
telemt_desync_frames_bucket_total{bucket="gt_10"} 111
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3735
telemt_me_writer_restored_same_endpoint_total 3679
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 169784
telemt_user_connections_current{user="hello"} 691
telemt_user_octets_from_client{user="hello"} 1496103420 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 52566306868 (48.96 GB)
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 20807.0 (5h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59662
telemt_connections_bad_total 125
telemt_handshake_timeouts_total 1044
telemt_upstream_connect_attempt_total 5917
telemt_upstream_connect_success_total 5914
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 5917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2958
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 4671
telemt_me_reconnect_success_total 4641
telemt_me_reader_eof_total 4921
telemt_me_idle_close_by_peer_total 4921
telemt_me_route_drop_no_conn_total 16813
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55747
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 130
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 67
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4676
telemt_me_writer_restored_same_endpoint_total 4632
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 55926
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 975851855 (930.64 MB)
telemt_user_octets_to_client{user="hello"} 19325846538 (18.00 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 20806.8 (5h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 322165
telemt_connections_bad_total 1534
telemt_handshake_timeouts_total 18478
telemt_upstream_connect_attempt_total 6271
telemt_upstream_connect_success_total 6269
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2666
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 4883
telemt_me_reconnect_success_total 4828
telemt_me_reader_eof_total 5019
telemt_me_idle_close_by_peer_total 5019
telemt_me_route_drop_no_conn_total 32568
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103539
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 274
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 181
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 137
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4790
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 4787
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 103861
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 877617632 (836.96 MB)
telemt_user_octets_to_client{user="hello"} 32202422229 (29.99 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 20807.3 (5h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93520
telemt_connections_bad_total 168
telemt_handshake_timeouts_total 4690
telemt_upstream_connect_attempt_total 6248
telemt_upstream_connect_success_total 6220
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 6248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2692
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 5157
telemt_me_reconnect_success_total 5138
telemt_me_reader_eof_total 5438
telemt_me_idle_close_by_peer_total 5438
telemt_me_route_drop_no_conn_total 31538
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87391
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 140
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 5171
telemt_me_writer_restored_same_endpoint_total 5117
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 87376
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 601140680 (573.29 MB)
telemt_user_octets_to_client{user="hello"} 22269252564 (20.74 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 20807.0 (5h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112225
telemt_connections_bad_total 70
telemt_handshake_timeouts_total 703
telemt_upstream_connect_attempt_total 7572
telemt_upstream_connect_success_total 7490
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 7572
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3672
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 7908
telemt_me_reconnect_success_total 6410
telemt_me_reader_eof_total 6667
telemt_me_idle_close_by_peer_total 6667
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 29321
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 107106
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 404
telemt_desync_full_logged_total 136
telemt_desync_suppressed_total 268
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 164
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 6503
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 6394
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 107082
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 656190668 (625.79 MB)
telemt_user_octets_to_client{user="hello"} 23144117368 (21.55 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 47
```