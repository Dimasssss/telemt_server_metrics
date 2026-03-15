# Server Metrics 2026-03-15 03:11:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 17842.9 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217535
telemt_connections_bad_total 2938
telemt_handshake_timeouts_total 698
telemt_upstream_connect_attempt_total 3772
telemt_upstream_connect_success_total 3758
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 3772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1800
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 2877
telemt_me_reconnect_success_total 2863
telemt_me_reader_eof_total 3023
telemt_me_idle_close_by_peer_total 3023
telemt_me_route_drop_no_conn_total 67167
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 192645
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 526
telemt_desync_full_logged_total 156
telemt_desync_suppressed_total 370
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 208
telemt_desync_frames_bucket_total{bucket="gt_10"} 201
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2896
telemt_me_writer_restored_same_endpoint_total 2852
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 192623
telemt_user_connections_current{user="hello"} 685
telemt_user_octets_from_client{user="hello"} 2055744792 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 70003229340 (65.20 GB)
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 17843.4 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87906
telemt_connections_bad_total 14572
telemt_handshake_timeouts_total 3713
telemt_upstream_connect_attempt_total 5254
telemt_upstream_connect_success_total 5231
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2826
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2368
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 4045
telemt_me_reconnect_success_total 4024
telemt_me_reader_eof_total 4225
telemt_me_idle_close_by_peer_total 4225
telemt_me_route_drop_no_conn_total 17420
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67415
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 114
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 88
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4012
telemt_me_writer_restored_same_endpoint_total 4016
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 67711
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 1609565631 (1.50 GB)
telemt_user_octets_to_client{user="hello"} 20986179896 (19.54 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 17843.6 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149962
telemt_connections_bad_total 3081
telemt_handshake_timeouts_total 13623
telemt_upstream_connect_attempt_total 4155
telemt_upstream_connect_success_total 4137
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1918
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3252
telemt_me_reconnect_success_total 3238
telemt_me_reader_eof_total 3414
telemt_me_idle_close_by_peer_total 3414
telemt_me_route_drop_no_conn_total 32750
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130458
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 271
telemt_desync_full_logged_total 136
telemt_desync_suppressed_total 135
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 106
telemt_desync_frames_bucket_total{bucket="gt_10"} 113
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3270
telemt_me_writer_restored_same_endpoint_total 3219
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 130367
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 1136534716 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 40405019572 (37.63 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 17843.5 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122205
telemt_connections_bad_total 29737
telemt_handshake_timeouts_total 3616
telemt_upstream_connect_attempt_total 6308
telemt_upstream_connect_success_total 6178
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 6308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3218
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 8827
telemt_me_reconnect_success_total 5276
telemt_me_reader_eof_total 5557
telemt_me_idle_close_by_peer_total 5557
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 24363
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87027
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5435
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 5257
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 87039
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 523761992 (499.50 MB)
telemt_user_octets_to_client{user="hello"} 24003605804 (22.36 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 17844.3 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74614
telemt_connections_bad_total 159
telemt_handshake_timeouts_total 972
telemt_upstream_connect_attempt_total 4093
telemt_upstream_connect_success_total 4075
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2382
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3189
telemt_me_reconnect_success_total 3176
telemt_me_reader_eof_total 3377
telemt_me_idle_close_by_peer_total 3377
telemt_me_route_drop_no_conn_total 19264
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71335
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 239
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 170
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3203
telemt_me_writer_restored_same_endpoint_total 3168
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 71333
telemt_user_connections_current{user="hello"} 266
telemt_user_octets_from_client{user="hello"} 606649592 (578.55 MB)
telemt_user_octets_to_client{user="hello"} 23043118272 (21.46 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 33
```