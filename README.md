# Server Metrics 2026-03-15 03:42:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 19675.6 (5h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 240844
telemt_connections_bad_total 3294
telemt_handshake_timeouts_total 1155
telemt_upstream_connect_attempt_total 4137
telemt_upstream_connect_success_total 4122
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 4137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1968
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 3155
telemt_me_reconnect_success_total 3140
telemt_me_reader_eof_total 3319
telemt_me_idle_close_by_peer_total 3319
telemt_me_route_drop_no_conn_total 74211
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 213155
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 550
telemt_desync_full_logged_total 166
telemt_desync_suppressed_total 384
telemt_desync_frames_bucket_total{bucket="1_2"} 118
telemt_desync_frames_bucket_total{bucket="3_10"} 225
telemt_desync_frames_bucket_total{bucket="gt_10"} 207
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3177
telemt_me_writer_restored_same_endpoint_total 3129
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 213131
telemt_user_connections_current{user="hello"} 802
telemt_user_octets_from_client{user="hello"} 2285582604 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 76290738284 (71.05 GB)
telemt_user_unique_ips_current{user="hello"} 287
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 19676.1 (5h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96338
telemt_connections_bad_total 16279
telemt_handshake_timeouts_total 3815
telemt_upstream_connect_attempt_total 5861
telemt_upstream_connect_success_total 5837
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2622
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 4564
telemt_me_reconnect_success_total 4541
telemt_me_reader_eof_total 4783
telemt_me_idle_close_by_peer_total 4783
telemt_me_route_drop_no_conn_total 19175
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73852
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 129
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 99
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4533
telemt_me_writer_restored_same_endpoint_total 4533
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 74148
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 1657164687 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 22147729000 (20.63 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 19676.4 (5h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166591
telemt_connections_bad_total 3219
telemt_handshake_timeouts_total 16004
telemt_upstream_connect_attempt_total 4543
telemt_upstream_connect_success_total 4524
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 4543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2082
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 3552
telemt_me_reconnect_success_total 3535
telemt_me_reader_eof_total 3727
telemt_me_idle_close_by_peer_total 3727
telemt_me_route_drop_no_conn_total 35997
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 144392
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 281
telemt_desync_full_logged_total 141
telemt_desync_suppressed_total 140
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3571
telemt_me_writer_restored_same_endpoint_total 3516
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 144289
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 1226536364 (1.14 GB)
telemt_user_octets_to_client{user="hello"} 43660451772 (40.66 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 19676.1 (5h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133442
telemt_connections_bad_total 31140
telemt_handshake_timeouts_total 5044
telemt_upstream_connect_attempt_total 6795
telemt_upstream_connect_success_total 6658
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 6795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3470
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 9221
telemt_me_reconnect_success_total 5668
telemt_me_reader_eof_total 5974
telemt_me_idle_close_by_peer_total 5974
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 26779
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95339
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
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 5830
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 5649
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 95348
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 708991568 (676.15 MB)
telemt_user_octets_to_client{user="hello"} 25590207860 (23.83 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 19677.2 (5h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81598
telemt_connections_bad_total 163
telemt_handshake_timeouts_total 1027
telemt_upstream_connect_attempt_total 4528
telemt_upstream_connect_success_total 4509
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 4528
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2622
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 3537
telemt_me_reconnect_success_total 3523
telemt_me_reader_eof_total 3752
telemt_me_idle_close_by_peer_total 3752
telemt_me_route_drop_no_conn_total 21465
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 78013
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 274
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 195
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3556
telemt_me_writer_restored_same_endpoint_total 3515
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 78011
telemt_user_connections_current{user="hello"} 324
telemt_user_octets_from_client{user="hello"} 653467136 (623.19 MB)
telemt_user_octets_to_client{user="hello"} 24837002504 (23.13 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 36
```