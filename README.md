# Server Metrics 2026-03-12 03:52:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 22030.9 (6h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195530
telemt_connections_bad_total 1368
telemt_handshake_timeouts_total 3460
telemt_upstream_connect_attempt_total 5058
telemt_upstream_connect_success_total 5058
telemt_upstream_connect_attempts_per_request{bucket="1"} 5058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2375
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 3952
telemt_me_reconnect_success_total 3936
telemt_me_reader_eof_total 4157
telemt_me_idle_close_by_peer_total 4157
telemt_me_route_drop_no_conn_total 69962
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185212
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 358
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 261
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 113
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3976
telemt_me_writer_restored_same_endpoint_total 3920
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 186
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 184995
telemt_user_connections_current{user="hello"} 716
telemt_user_octets_from_client{user="hello"} 1671981744 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 58003559276 (54.02 GB)
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 22031.6 (6h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65053
telemt_connections_bad_total 128
telemt_handshake_timeouts_total 1211
telemt_upstream_connect_attempt_total 6230
telemt_upstream_connect_success_total 6227
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3127
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 4939
telemt_me_reconnect_success_total 4908
telemt_me_reader_eof_total 5209
telemt_me_idle_close_by_peer_total 5209
telemt_me_route_drop_no_conn_total 18450
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60760
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 161
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4945
telemt_me_writer_restored_same_endpoint_total 4899
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 60938
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 1015388031 (968.35 MB)
telemt_user_octets_to_client{user="hello"} 20894273938 (19.46 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 22031.4 (6h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 333285
telemt_connections_bad_total 1753
telemt_handshake_timeouts_total 19989
telemt_upstream_connect_attempt_total 6579
telemt_upstream_connect_success_total 6577
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2826
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 109
telemt_me_reconnect_attempts_total 5148
telemt_me_reconnect_success_total 5092
telemt_me_reader_eof_total 5307
telemt_me_idle_close_by_peer_total 5307
telemt_me_route_drop_no_conn_total 35145
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112459
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 329
telemt_desync_full_logged_total 117
telemt_desync_suppressed_total 212
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 173
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5058
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 5051
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 112783
telemt_user_connections_current{user="hello"} 354
telemt_user_octets_from_client{user="hello"} 1032713020 (984.87 MB)
telemt_user_octets_to_client{user="hello"} 34528722113 (32.16 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 22031.8 (6h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100409
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 5402
telemt_upstream_connect_attempt_total 6579
telemt_upstream_connect_success_total 6551
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 6579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2823
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 5443
telemt_me_reconnect_success_total 5423
telemt_me_reader_eof_total 5754
telemt_me_idle_close_by_peer_total 5754
telemt_me_route_drop_no_conn_total 34195
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93463
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 147
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 101
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 5458
telemt_me_writer_restored_same_endpoint_total 5402
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 93455
telemt_user_connections_current{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 707740236 (674.95 MB)
telemt_user_octets_to_client{user="hello"} 24127022036 (22.47 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 22031.6 (6h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119639
telemt_connections_bad_total 70
telemt_handshake_timeouts_total 720
telemt_upstream_connect_attempt_total 8148
telemt_upstream_connect_success_total 8063
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 8147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3912
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 122
telemt_me_reconnect_attempts_total 8425
telemt_me_reconnect_success_total 6924
telemt_me_reader_eof_total 7187
telemt_me_idle_close_by_peer_total 7187
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 31856
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114353
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 426
telemt_desync_full_logged_total 148
telemt_desync_suppressed_total 278
telemt_desync_frames_bucket_total{bucket="1_2"} 115
telemt_desync_frames_bucket_total{bucket="3_10"} 172
telemt_desync_frames_bucket_total{bucket="gt_10"} 139
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 7024
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 6907
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 114328
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 707568896 (674.79 MB)
telemt_user_octets_to_client{user="hello"} 25105132160 (23.38 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 46
```