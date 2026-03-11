# Server Metrics 2026-03-11 15:52:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 91542.7 (25h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2264868
telemt_connections_bad_total 39307
telemt_handshake_timeouts_total 53364
telemt_upstream_connect_attempt_total 19136
telemt_upstream_connect_success_total 19124
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 19136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9412
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 4895
telemt_me_reconnect_attempts_total 32365
telemt_me_reconnect_success_total 14497
telemt_me_reader_eof_total 15733
telemt_me_idle_close_by_peer_total 15733
telemt_me_route_drop_no_conn_total 838654
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2071146
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10778
telemt_desync_full_logged_total 2931
telemt_desync_suppressed_total 7847
telemt_desync_frames_bucket_total{bucket="1_2"} 2673
telemt_desync_frames_bucket_total{bucket="3_10"} 4152
telemt_desync_frames_bucket_total{bucket="gt_10"} 3953
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 15215
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 14491
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 718
telemt_user_connections_total{user="hello"} 2069589
telemt_user_connections_current{user="hello"} 1375
telemt_user_octets_from_client{user="hello"} 27692084264 (25.79 GB)
telemt_user_octets_to_client{user="hello"} 586443149872 (546.17 GB)
telemt_user_unique_ips_current{user="hello"} 383
telemt_user_unique_ips_recent_window{user="hello"} 206
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 91599.4 (25h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 838440
telemt_connections_bad_total 14044
telemt_handshake_timeouts_total 57095
telemt_upstream_connect_attempt_total 29049
telemt_upstream_connect_success_total 26091
telemt_upstream_connect_fail_total 2958
telemt_upstream_connect_attempts_per_request{bucket="1"} 29049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11694
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2958
telemt_me_keepalive_timeout_total 2560
telemt_me_reconnect_attempts_total 20643
telemt_me_reconnect_success_total 18550
telemt_me_reader_eof_total 19641
telemt_me_idle_close_by_peer_total 19638
telemt_me_route_drop_no_conn_total 328200
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 712728
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2912
telemt_desync_full_logged_total 930
telemt_desync_suppressed_total 1982
telemt_desync_frames_bucket_total{bucket="1_2"} 903
telemt_desync_frames_bucket_total{bucket="3_10"} 1044
telemt_desync_frames_bucket_total{bucket="gt_10"} 965
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 18817
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 18527
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 715205
telemt_user_connections_current{user="hello"} 492
telemt_user_octets_from_client{user="hello"} 8262055662 (7.69 GB)
telemt_user_octets_to_client{user="hello"} 202909197680 (188.97 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 91599.3 (25h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1452696
telemt_connections_bad_total 8687
telemt_handshake_timeouts_total 124464
telemt_upstream_connect_attempt_total 23959
telemt_upstream_connect_success_total 23666
telemt_upstream_connect_fail_total 293
telemt_upstream_connect_attempts_per_request{bucket="1"} 23959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10763
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 293
telemt_me_keepalive_timeout_total 1589
telemt_me_reconnect_attempts_total 39023
telemt_me_reconnect_success_total 17979
telemt_me_reader_eof_total 19442
telemt_me_idle_close_by_peer_total 19442
telemt_me_route_drop_no_conn_total 530294
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1266784
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3339
telemt_desync_full_logged_total 989
telemt_desync_suppressed_total 2350
telemt_desync_frames_bucket_total{bucket="1_2"} 820
telemt_desync_frames_bucket_total{bucket="3_10"} 1266
telemt_desync_frames_bucket_total{bucket="gt_10"} 1253
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 18881
telemt_me_refill_failed_total 653
telemt_me_writer_restored_same_endpoint_total 17968
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 902
telemt_user_connections_total{user="hello"} 1266499
telemt_user_connections_current{user="hello"} 802
telemt_user_octets_from_client{user="hello"} 15232601017 (14.19 GB)
telemt_user_octets_to_client{user="hello"} 382404572397 (356.14 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 91599.9 (25h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1043989
telemt_connections_bad_total 77970
telemt_handshake_timeouts_total 101966
telemt_upstream_connect_attempt_total 24599
telemt_upstream_connect_success_total 24599
telemt_upstream_connect_attempts_per_request{bucket="1"} 24599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13457
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1016
telemt_me_reconnect_attempts_total 21111
telemt_me_reconnect_success_total 20036
telemt_me_reader_eof_total 21227
telemt_me_idle_close_by_peer_total 21226
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 341942
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 835612
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1744
telemt_desync_full_logged_total 670
telemt_desync_suppressed_total 1074
telemt_desync_frames_bucket_total{bucket="1_2"} 627
telemt_desync_frames_bucket_total{bucket="3_10"} 612
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 20279
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 20006
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 834931
telemt_user_connections_current{user="hello"} 629
telemt_user_octets_from_client{user="hello"} 9989281516 (9.30 GB)
telemt_user_octets_to_client{user="hello"} 247083406304 (230.11 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 91599.7 (25h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1154931
telemt_connections_bad_total 6940
telemt_handshake_timeouts_total 11599
telemt_upstream_connect_attempt_total 24854
telemt_upstream_connect_success_total 24743
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 24854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11905
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 200
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 1953
telemt_me_reconnect_attempts_total 24126
telemt_me_reconnect_success_total 20035
telemt_me_reader_eof_total 21111
telemt_me_idle_close_by_peer_total 21111
telemt_me_route_drop_no_conn_total 411845
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1051107
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4058
telemt_desync_full_logged_total 1466
telemt_desync_suppressed_total 2592
telemt_desync_frames_bucket_total{bucket="1_2"} 1359
telemt_desync_frames_bucket_total{bucket="3_10"} 1521
telemt_desync_frames_bucket_total{bucket="gt_10"} 1178
telemt_pool_swap_total 60
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20421
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 20035
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 386
telemt_user_connections_total{user="hello"} 1050811
telemt_user_connections_current{user="hello"} 748
telemt_user_octets_from_client{user="hello"} 18880470551 (17.58 GB)
telemt_user_octets_to_client{user="hello"} 366999008838 (341.79 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 106
```