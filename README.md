# Server Metrics 2026-03-11 13:40:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 83574.3 (23h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1978161
telemt_connections_bad_total 27776
telemt_handshake_timeouts_total 50826
telemt_upstream_connect_attempt_total 17340
telemt_upstream_connect_success_total 17331
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 17340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8488
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 957
telemt_me_reconnect_attempts_total 25953
telemt_me_reconnect_success_total 13121
telemt_me_reader_eof_total 14174
telemt_me_idle_close_by_peer_total 14174
telemt_me_route_drop_no_conn_total 727476
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1808271
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9550
telemt_desync_full_logged_total 2583
telemt_desync_suppressed_total 6967
telemt_desync_frames_bucket_total{bucket="1_2"} 2358
telemt_desync_frames_bucket_total{bucket="3_10"} 3687
telemt_desync_frames_bucket_total{bucket="gt_10"} 3505
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 13661
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 13115
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 540
telemt_user_connections_total{user="hello"} 1806784
telemt_user_connections_current{user="hello"} 1482
telemt_user_octets_from_client{user="hello"} 24094330964 (22.44 GB)
telemt_user_octets_to_client{user="hello"} 515351657084 (479.96 GB)
telemt_user_unique_ips_current{user="hello"} 394
telemt_user_unique_ips_recent_window{user="hello"} 183
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 83631.1 (23h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 749092
telemt_connections_bad_total 13053
telemt_handshake_timeouts_total 51104
telemt_upstream_connect_attempt_total 26812
telemt_upstream_connect_success_total 23865
telemt_upstream_connect_fail_total 2947
telemt_upstream_connect_attempts_per_request{bucket="1"} 26812
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10621
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2947
telemt_me_keepalive_timeout_total 2458
telemt_me_reconnect_attempts_total 17604
telemt_me_reconnect_success_total 16738
telemt_me_reader_eof_total 17706
telemt_me_idle_close_by_peer_total 17703
telemt_me_route_drop_no_conn_total 292802
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 632211
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2752
telemt_desync_full_logged_total 871
telemt_desync_suppressed_total 1881
telemt_desync_frames_bucket_total{bucket="1_2"} 860
telemt_desync_frames_bucket_total{bucket="3_10"} 1003
telemt_desync_frames_bucket_total{bucket="gt_10"} 889
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 16949
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 16715
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 211
telemt_user_connections_total{user="hello"} 634698
telemt_user_connections_current{user="hello"} 516
telemt_user_octets_from_client{user="hello"} 6817629270 (6.35 GB)
telemt_user_octets_to_client{user="hello"} 180351723408 (167.97 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 83631.1 (23h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1292674
telemt_connections_bad_total 8305
telemt_handshake_timeouts_total 118660
telemt_upstream_connect_attempt_total 22194
telemt_upstream_connect_success_total 21926
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 22194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9957
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_keepalive_timeout_total 900
telemt_me_reconnect_attempts_total 32760
telemt_me_reconnect_success_total 16655
telemt_me_reader_eof_total 17920
telemt_me_idle_close_by_peer_total 17920
telemt_me_route_drop_no_conn_total 448099
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1117282
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2978
telemt_desync_full_logged_total 881
telemt_desync_suppressed_total 2097
telemt_desync_frames_bucket_total{bucket="1_2"} 718
telemt_desync_frames_bucket_total{bucket="3_10"} 1124
telemt_desync_frames_bucket_total{bucket="gt_10"} 1136
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 17378
telemt_me_refill_failed_total 499
telemt_me_writer_restored_same_endpoint_total 16644
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 723
telemt_user_connections_total{user="hello"} 1117652
telemt_user_connections_current{user="hello"} 786
telemt_user_octets_from_client{user="hello"} 13196879605 (12.29 GB)
telemt_user_octets_to_client{user="hello"} 334423778605 (311.46 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 83631.4 (23h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 930393
telemt_connections_bad_total 77220
telemt_handshake_timeouts_total 88137
telemt_upstream_connect_attempt_total 22710
telemt_upstream_connect_success_total 22710
telemt_upstream_connect_attempts_per_request{bucket="1"} 22710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10264
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 939
telemt_me_reconnect_attempts_total 19615
telemt_me_reconnect_success_total 18546
telemt_me_reader_eof_total 19670
telemt_me_idle_close_by_peer_total 19669
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 299839
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 739549
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1595
telemt_desync_full_logged_total 623
telemt_desync_suppressed_total 972
telemt_desync_frames_bucket_total{bucket="1_2"} 576
telemt_desync_frames_bucket_total{bucket="3_10"} 562
telemt_desync_frames_bucket_total{bucket="gt_10"} 457
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18775
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 18518
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 738909
telemt_user_connections_current{user="hello"} 514
telemt_user_octets_from_client{user="hello"} 8580609796 (7.99 GB)
telemt_user_octets_to_client{user="hello"} 214628270288 (199.89 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 83631.1 (23h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1015755
telemt_connections_bad_total 6819
telemt_handshake_timeouts_total 9317
telemt_upstream_connect_attempt_total 22762
telemt_upstream_connect_success_total 22664
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 22762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11635
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10842
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 969
telemt_me_reconnect_attempts_total 22445
telemt_me_reconnect_success_total 18372
telemt_me_reader_eof_total 19385
telemt_me_idle_close_by_peer_total 19385
telemt_me_route_drop_no_conn_total 359058
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 922452
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3700
telemt_desync_full_logged_total 1364
telemt_desync_suppressed_total 2336
telemt_desync_frames_bucket_total{bucket="1_2"} 1300
telemt_desync_frames_bucket_total{bucket="3_10"} 1395
telemt_desync_frames_bucket_total{bucket="gt_10"} 1005
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18735
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 18372
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 363
telemt_user_connections_total{user="hello"} 922193
telemt_user_connections_current{user="hello"} 789
telemt_user_octets_from_client{user="hello"} 13481935743 (12.56 GB)
telemt_user_octets_to_client{user="hello"} 328902686518 (306.31 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 118
```