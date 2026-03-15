# Server Metrics 2026-03-15 03:47:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 19980.9 (5h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244926
telemt_connections_bad_total 3385
telemt_handshake_timeouts_total 1196
telemt_upstream_connect_attempt_total 4237
telemt_upstream_connect_success_total 4220
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 4237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2207
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2009
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 3209
telemt_me_reconnect_success_total 3193
telemt_me_reader_eof_total 3373
telemt_me_idle_close_by_peer_total 3373
telemt_me_route_drop_no_conn_total 75394
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 216706
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 568
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 397
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 230
telemt_desync_frames_bucket_total{bucket="gt_10"} 216
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3231
telemt_me_writer_restored_same_endpoint_total 3182
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 216682
telemt_user_connections_current{user="hello"} 712
telemt_user_octets_from_client{user="hello"} 2316336088 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 77339681764 (72.03 GB)
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 19981.6 (5h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97931
telemt_connections_bad_total 16433
telemt_handshake_timeouts_total 3825
telemt_upstream_connect_attempt_total 5982
telemt_upstream_connect_success_total 5957
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 5982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2667
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_reconnect_attempts_total 4641
telemt_me_reconnect_success_total 4617
telemt_me_reader_eof_total 4876
telemt_me_idle_close_by_peer_total 4876
telemt_me_route_drop_no_conn_total 19479
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75232
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 130
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 99
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4610
telemt_me_writer_restored_same_endpoint_total 4609
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 75528
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 1668920783 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 22472244196 (20.93 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 19981.8 (5h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169296
telemt_connections_bad_total 3220
telemt_handshake_timeouts_total 16246
telemt_upstream_connect_attempt_total 4653
telemt_upstream_connect_success_total 4634
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 4653
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2129
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 3619
telemt_me_reconnect_success_total 3602
telemt_me_reader_eof_total 3803
telemt_me_idle_close_by_peer_total 3803
telemt_me_route_drop_no_conn_total 36619
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146784
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 282
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 140
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3638
telemt_me_writer_restored_same_endpoint_total 3583
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 146681
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 1242693600 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 44900718864 (41.82 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 19981.6 (5h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135497
telemt_connections_bad_total 31377
telemt_handshake_timeouts_total 5384
telemt_upstream_connect_attempt_total 6920
telemt_upstream_connect_success_total 6778
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 6920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3520
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 9298
telemt_me_reconnect_success_total 5745
telemt_me_reader_eof_total 6050
telemt_me_idle_close_by_peer_total 6050
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 27300
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96801
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 25
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
telemt_me_writer_removed_unexpected_total 5907
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 5725
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 96806
telemt_user_connections_current{user="hello"} 290
telemt_user_octets_from_client{user="hello"} 728806584 (695.04 MB)
telemt_user_octets_to_client{user="hello"} 26083467844 (24.29 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 19982.6 (5h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82685
telemt_connections_bad_total 163
telemt_handshake_timeouts_total 1032
telemt_upstream_connect_attempt_total 4631
telemt_upstream_connect_success_total 4610
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 4631
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1929
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2676
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 3594
telemt_me_reconnect_success_total 3580
telemt_me_reader_eof_total 3819
telemt_me_idle_close_by_peer_total 3819
telemt_me_route_drop_no_conn_total 21712
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79065
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 281
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 200
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3613
telemt_me_writer_restored_same_endpoint_total 3572
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 79063
telemt_user_connections_current{user="hello"} 268
telemt_user_octets_from_client{user="hello"} 664965516 (634.16 MB)
telemt_user_octets_to_client{user="hello"} 25333666716 (23.59 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 33
```