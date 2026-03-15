# Server Metrics 2026-03-15 04:28:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 22424.1 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 281761
telemt_connections_bad_total 3841
telemt_handshake_timeouts_total 1379
telemt_upstream_connect_attempt_total 4750
telemt_upstream_connect_success_total 4732
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 4750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2233
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 3635
telemt_me_reconnect_success_total 3616
telemt_me_reader_eof_total 3819
telemt_me_idle_close_by_peer_total 3819
telemt_me_route_drop_no_conn_total 88958
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 249917
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 646
telemt_desync_full_logged_total 191
telemt_desync_suppressed_total 455
telemt_desync_frames_bucket_total{bucket="1_2"} 137
telemt_desync_frames_bucket_total{bucket="3_10"} 265
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3656
telemt_me_writer_restored_same_endpoint_total 3605
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 249888
telemt_user_connections_current{user="hello"} 872
telemt_user_octets_from_client{user="hello"} 2624705344 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 88937127796 (82.83 GB)
telemt_user_unique_ips_current{user="hello"} 321
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 22424.6 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111572
telemt_connections_bad_total 18081
telemt_handshake_timeouts_total 4357
telemt_upstream_connect_attempt_total 6663
telemt_upstream_connect_success_total 6636
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2936
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 5233
telemt_me_reconnect_success_total 5207
telemt_me_reader_eof_total 5499
telemt_me_idle_close_by_peer_total 5499
telemt_me_route_drop_no_conn_total 23037
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86380
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 162
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 117
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5210
telemt_me_writer_restored_same_endpoint_total 5199
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 86676
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 1760608807 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 25087681792 (23.36 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 22424.9 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198333
telemt_connections_bad_total 3628
telemt_handshake_timeouts_total 21679
telemt_upstream_connect_attempt_total 5234
telemt_upstream_connect_success_total 5213
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 5234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2378
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 4110
telemt_me_reconnect_success_total 4091
telemt_me_reader_eof_total 4321
telemt_me_idle_close_by_peer_total 4321
telemt_me_route_drop_no_conn_total 43774
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169002
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 293
telemt_desync_full_logged_total 152
telemt_desync_suppressed_total 141
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4133
telemt_me_writer_restored_same_endpoint_total 4072
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 168876
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 1386671440 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 52642886916 (49.03 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 22424.7 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153275
telemt_connections_bad_total 33261
telemt_handshake_timeouts_total 8294
telemt_upstream_connect_attempt_total 7974
telemt_upstream_connect_success_total 7803
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 7974
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4065
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 11452
telemt_me_reconnect_success_total 6682
telemt_me_reader_eof_total 7033
telemt_me_idle_close_by_peer_total 7033
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 32177
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109573
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 160
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 67
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 6890
telemt_me_refill_failed_total 148
telemt_me_writer_restored_same_endpoint_total 6662
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 109576
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 921138156 (878.47 MB)
telemt_user_octets_to_client{user="hello"} 36988245144 (34.45 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 22425.6 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94305
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 1102
telemt_upstream_connect_attempt_total 5167
telemt_upstream_connect_success_total 5143
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2965
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 4040
telemt_me_reconnect_success_total 4023
telemt_me_reader_eof_total 4287
telemt_me_idle_close_by_peer_total 4287
telemt_me_route_drop_no_conn_total 25085
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 90204
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 389
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 274
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 149
telemt_desync_frames_bucket_total{bucket="gt_10"} 107
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4062
telemt_me_writer_restored_same_endpoint_total 4015
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 90202
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 764174976 (728.77 MB)
telemt_user_octets_to_client{user="hello"} 28135105748 (26.20 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 44
```