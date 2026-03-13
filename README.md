# Server Metrics 2026-03-13 02:34:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 74148.6 (20h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2090913
telemt_connections_bad_total 27792
telemt_handshake_timeouts_total 22224
telemt_upstream_connect_attempt_total 14691
telemt_upstream_connect_success_total 14608
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 14691
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7042
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 1264
telemt_me_reconnect_attempts_total 19756
telemt_me_reconnect_success_total 10895
telemt_me_reader_eof_total 11772
telemt_me_idle_close_by_peer_total 11771
telemt_me_route_drop_no_conn_total 807100
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1929661
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8706
telemt_desync_full_logged_total 2268
telemt_desync_suppressed_total 6438
telemt_desync_frames_bucket_total{bucket="1_2"} 2297
telemt_desync_frames_bucket_total{bucket="3_10"} 3139
telemt_desync_frames_bucket_total{bucket="gt_10"} 3270
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 11325
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 10882
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 430
telemt_user_connections_total{user="hello"} 1929118
telemt_user_connections_current{user="hello"} 594
telemt_user_octets_from_client{user="hello"} 28112562100 (26.18 GB)
telemt_user_octets_to_client{user="hello"} 671208418048 (625.11 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 103769.1 (28h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 854479
telemt_connections_bad_total 11817
telemt_handshake_timeouts_total 32384
telemt_upstream_connect_attempt_total 26448
telemt_upstream_connect_success_total 26419
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 26448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13717
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12612
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3453
telemt_me_reconnect_attempts_total 19701
telemt_me_reconnect_success_total 19593
telemt_me_reader_eof_total 20879
telemt_me_idle_close_by_peer_total 20879
telemt_me_route_drop_no_conn_total 274817
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 775061
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3097
telemt_desync_full_logged_total 973
telemt_desync_suppressed_total 2124
telemt_desync_frames_bucket_total{bucket="1_2"} 1254
telemt_desync_frames_bucket_total{bucket="3_10"} 1006
telemt_desync_frames_bucket_total{bucket="gt_10"} 837
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 19785
telemt_me_writer_restored_same_endpoint_total 19584
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 192
telemt_user_connections_total{user="hello"} 776964
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 12372040144 (11.52 GB)
telemt_user_octets_to_client{user="hello"} 292692929563 (272.59 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 103769.0 (28h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1772419
telemt_connections_bad_total 9183
telemt_handshake_timeouts_total 118489
telemt_upstream_connect_attempt_total 24228
telemt_upstream_connect_success_total 24217
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 24227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11377
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1605
telemt_me_reconnect_attempts_total 19945
telemt_me_reconnect_success_total 18681
telemt_me_reader_eof_total 19788
telemt_me_idle_close_by_peer_total 19787
telemt_me_route_drop_no_conn_total 578026
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1395475
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5022
telemt_desync_full_logged_total 1538
telemt_desync_suppressed_total 3484
telemt_desync_frames_bucket_total{bucket="1_2"} 804
telemt_desync_frames_bucket_total{bucket="3_10"} 1818
telemt_desync_frames_bucket_total{bucket="gt_10"} 2400
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 18856
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 18640
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 1395070
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 20206546588 (18.82 GB)
telemt_user_octets_to_client{user="hello"} 502900695713 (468.36 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 103769.2 (28h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1107350
telemt_connections_bad_total 13138
telemt_handshake_timeouts_total 73275
telemt_upstream_connect_attempt_total 36302
telemt_upstream_connect_success_total 34029
telemt_upstream_connect_fail_total 2136
telemt_upstream_connect_attempts_per_request{bucket="1"} 36028
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12843
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2135
telemt_me_keepalive_timeout_total 11362
telemt_me_reconnect_attempts_total 31904
telemt_me_reconnect_success_total 22980
telemt_me_reader_eof_total 24823
telemt_me_idle_close_by_peer_total 24816
telemt_me_route_drop_no_conn_total 392325
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 949536
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1896
telemt_desync_full_logged_total 629
telemt_desync_suppressed_total 1267
telemt_desync_frames_bucket_total{bucket="1_2"} 523
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 23409
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 22956
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 429
telemt_user_connections_total{user="hello"} 954709
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 14550530957 (13.55 GB)
telemt_user_octets_to_client{user="hello"} 374523229230 (348.80 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 103769.0 (28h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1223984
telemt_connections_bad_total 12627
telemt_handshake_timeouts_total 9550
telemt_upstream_connect_attempt_total 32897
telemt_upstream_connect_success_total 32494
telemt_upstream_connect_fail_total 403
telemt_upstream_connect_attempts_per_request{bucket="1"} 32897
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15656
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 403
telemt_me_keepalive_timeout_total 1893
telemt_me_reconnect_attempts_total 41040
telemt_me_reconnect_success_total 27310
telemt_me_reader_eof_total 28737
telemt_me_idle_close_by_peer_total 28737
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 457513
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1131780
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4203
telemt_desync_full_logged_total 1492
telemt_desync_suppressed_total 2711
telemt_desync_frames_bucket_total{bucket="1_2"} 1259
telemt_desync_frames_bucket_total{bucket="3_10"} 1390
telemt_desync_frames_bucket_total{bucket="gt_10"} 1554
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 28050
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 27261
telemt_me_writer_restored_fallback_total 49
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 740
telemt_user_connections_total{user="hello"} 1131635
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 13975665092 (13.02 GB)
telemt_user_octets_to_client{user="hello"} 391096820416 (364.24 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 41
```