# Server Metrics 2026-03-11 16:23:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 93382.4 (25h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2327024
telemt_connections_bad_total 40443
telemt_handshake_timeouts_total 53880
telemt_upstream_connect_attempt_total 19531
telemt_upstream_connect_success_total 19519
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 19531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9600
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5008
telemt_me_reconnect_attempts_total 32670
telemt_me_reconnect_success_total 14796
telemt_me_reader_eof_total 16048
telemt_me_idle_close_by_peer_total 16048
telemt_me_route_drop_no_conn_total 863565
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2128350
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11089
telemt_desync_full_logged_total 3022
telemt_desync_suppressed_total 8067
telemt_desync_frames_bucket_total{bucket="1_2"} 2743
telemt_desync_frames_bucket_total{bucket="3_10"} 4281
telemt_desync_frames_bucket_total{bucket="gt_10"} 4065
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 15517
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 14790
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 721
telemt_user_connections_total{user="hello"} 2126810
telemt_user_connections_current{user="hello"} 1404
telemt_user_octets_from_client{user="hello"} 28747038204 (26.77 GB)
telemt_user_octets_to_client{user="hello"} 600261193252 (559.04 GB)
telemt_user_unique_ips_current{user="hello"} 385
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 93439.2 (25h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 868660
telemt_connections_bad_total 14892
telemt_handshake_timeouts_total 67254
telemt_upstream_connect_attempt_total 29422
telemt_upstream_connect_success_total 26464
telemt_upstream_connect_fail_total 2958
telemt_upstream_connect_attempts_per_request{bucket="1"} 29422
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11867
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2958
telemt_me_keepalive_timeout_total 2637
telemt_me_reconnect_attempts_total 20927
telemt_me_reconnect_success_total 18832
telemt_me_reader_eof_total 19939
telemt_me_idle_close_by_peer_total 19936
telemt_me_route_drop_no_conn_total 335464
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 731470
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2941
telemt_desync_full_logged_total 937
telemt_desync_suppressed_total 2004
telemt_desync_frames_bucket_total{bucket="1_2"} 907
telemt_desync_frames_bucket_total{bucket="3_10"} 1054
telemt_desync_frames_bucket_total{bucket="gt_10"} 980
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 19102
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 18809
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 733930
telemt_user_connections_current{user="hello"} 476
telemt_user_octets_from_client{user="hello"} 8391525142 (7.82 GB)
telemt_user_octets_to_client{user="hello"} 207457989652 (193.21 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 93439.3 (25h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1489789
telemt_connections_bad_total 8911
telemt_handshake_timeouts_total 125390
telemt_upstream_connect_attempt_total 24178
telemt_upstream_connect_success_total 23872
telemt_upstream_connect_fail_total 306
telemt_upstream_connect_attempts_per_request{bucket="1"} 24178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10865
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 306
telemt_me_keepalive_timeout_total 1716
telemt_me_reconnect_attempts_total 41845
telemt_me_reconnect_success_total 18093
telemt_me_reader_eof_total 19640
telemt_me_idle_close_by_peer_total 19640
telemt_me_route_drop_no_conn_total 544929
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1301616
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3429
telemt_desync_full_logged_total 1016
telemt_desync_suppressed_total 2413
telemt_desync_frames_bucket_total{bucket="1_2"} 852
telemt_desync_frames_bucket_total{bucket="3_10"} 1293
telemt_desync_frames_bucket_total{bucket="gt_10"} 1284
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 19080
telemt_me_refill_failed_total 737
telemt_me_writer_restored_same_endpoint_total 18081
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 987
telemt_user_connections_total{user="hello"} 1301327
telemt_user_connections_current{user="hello"} 846
telemt_user_octets_from_client{user="hello"} 15774963365 (14.69 GB)
telemt_user_octets_to_client{user="hello"} 395315895221 (368.17 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 93439.6 (25h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1074300
telemt_connections_bad_total 77973
telemt_handshake_timeouts_total 103744
telemt_upstream_connect_attempt_total 25069
telemt_upstream_connect_success_total 25069
telemt_upstream_connect_attempts_per_request{bucket="1"} 25069
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11360
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1085
telemt_me_reconnect_attempts_total 21493
telemt_me_reconnect_success_total 20416
telemt_me_reader_eof_total 21634
telemt_me_idle_close_by_peer_total 21633
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 352196
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 860501
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1785
telemt_desync_full_logged_total 689
telemt_desync_suppressed_total 1096
telemt_desync_frames_bucket_total{bucket="1_2"} 648
telemt_desync_frames_bucket_total{bucket="3_10"} 624
telemt_desync_frames_bucket_total{bucket="gt_10"} 513
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 20663
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 20385
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 859817
telemt_user_connections_current{user="hello"} 575
telemt_user_octets_from_client{user="hello"} 10339496744 (9.63 GB)
telemt_user_octets_to_client{user="hello"} 253971725144 (236.53 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 93439.3 (25h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1184129
telemt_connections_bad_total 6948
telemt_handshake_timeouts_total 11792
telemt_upstream_connect_attempt_total 25461
telemt_upstream_connect_success_total 25347
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 25461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12943
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12199
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 200
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 2110
telemt_me_reconnect_attempts_total 24642
telemt_me_reconnect_success_total 20547
telemt_me_reader_eof_total 21655
telemt_me_idle_close_by_peer_total 21655
telemt_me_route_drop_no_conn_total 422976
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1078370
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4204
telemt_desync_full_logged_total 1501
telemt_desync_suppressed_total 2703
telemt_desync_frames_bucket_total{bucket="1_2"} 1391
telemt_desync_frames_bucket_total{bucket="3_10"} 1572
telemt_desync_frames_bucket_total{bucket="gt_10"} 1241
telemt_pool_swap_total 61
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 20941
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 20547
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 394
telemt_user_connections_total{user="hello"} 1078071
telemt_user_connections_current{user="hello"} 643
telemt_user_octets_from_client{user="hello"} 20301904459 (18.91 GB)
telemt_user_octets_to_client{user="hello"} 374510746530 (348.79 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 98
```