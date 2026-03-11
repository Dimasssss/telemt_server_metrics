# Server Metrics 2026-03-11 18:51:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 102265.4 (28h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2595227
telemt_connections_bad_total 48539
telemt_handshake_timeouts_total 56811
telemt_upstream_connect_attempt_total 21552
telemt_upstream_connect_success_total 21540
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 21552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10545
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5316
telemt_me_reconnect_attempts_total 34249
telemt_me_reconnect_success_total 16367
telemt_me_reader_eof_total 17704
telemt_me_idle_close_by_peer_total 17704
telemt_me_route_drop_no_conn_total 977167
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2374006
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12014
telemt_desync_full_logged_total 3322
telemt_desync_suppressed_total 8692
telemt_desync_frames_bucket_total{bucket="1_2"} 2950
telemt_desync_frames_bucket_total{bucket="3_10"} 4629
telemt_desync_frames_bucket_total{bucket="gt_10"} 4435
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 17109
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 16361
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 742
telemt_user_connections_total{user="hello"} 2372357
telemt_user_connections_current{user="hello"} 1216
telemt_user_octets_from_client{user="hello"} 35451153988 (33.02 GB)
telemt_user_octets_to_client{user="hello"} 673444894804 (627.19 GB)
telemt_user_unique_ips_current{user="hello"} 351
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 102322.1 (28h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 970468
telemt_connections_bad_total 16419
telemt_handshake_timeouts_total 86475
telemt_upstream_connect_attempt_total 31721
telemt_upstream_connect_success_total 28752
telemt_upstream_connect_fail_total 2969
telemt_upstream_connect_attempts_per_request{bucket="1"} 31721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12929
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2046
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2969
telemt_me_keepalive_timeout_total 2830
telemt_me_reconnect_attempts_total 22771
telemt_me_reconnect_success_total 20659
telemt_me_reader_eof_total 21859
telemt_me_idle_close_by_peer_total 21856
telemt_me_route_drop_no_conn_total 366459
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 809658
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3209
telemt_desync_full_logged_total 1040
telemt_desync_suppressed_total 2169
telemt_desync_frames_bucket_total{bucket="1_2"} 1011
telemt_desync_frames_bucket_total{bucket="3_10"} 1145
telemt_desync_frames_bucket_total{bucket="gt_10"} 1053
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 20947
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 20636
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 288
telemt_user_connections_total{user="hello"} 812110
telemt_user_connections_current{user="hello"} 507
telemt_user_octets_from_client{user="hello"} 9773453190 (9.10 GB)
telemt_user_octets_to_client{user="hello"} 234456116668 (218.35 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 102322.0 (28h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1668813
telemt_connections_bad_total 10475
telemt_handshake_timeouts_total 133320
telemt_upstream_connect_attempt_total 26547
telemt_upstream_connect_success_total 26215
telemt_upstream_connect_fail_total 332
telemt_upstream_connect_attempts_per_request{bucket="1"} 26547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11951
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 332
telemt_me_keepalive_timeout_total 1970
telemt_me_reconnect_attempts_total 48316
telemt_me_reconnect_success_total 19973
telemt_me_reader_eof_total 21716
telemt_me_idle_close_by_peer_total 21716
telemt_me_route_drop_no_conn_total 607717
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1461609
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4048
telemt_desync_full_logged_total 1188
telemt_desync_suppressed_total 2860
telemt_desync_frames_bucket_total{bucket="1_2"} 946
telemt_desync_frames_bucket_total{bucket="3_10"} 1533
telemt_desync_frames_bucket_total{bucket="gt_10"} 1569
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 21136
telemt_me_refill_failed_total 880
telemt_me_writer_restored_same_endpoint_total 19961
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1163
telemt_user_connections_total{user="hello"} 1461277
telemt_user_connections_current{user="hello"} 640
telemt_user_octets_from_client{user="hello"} 18599184757 (17.32 GB)
telemt_user_octets_to_client{user="hello"} 444859168173 (414.31 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 102322.4 (28h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1190337
telemt_connections_bad_total 78200
telemt_handshake_timeouts_total 110339
telemt_upstream_connect_attempt_total 27553
telemt_upstream_connect_success_total 27553
telemt_upstream_connect_attempts_per_request{bucket="1"} 27553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1417
telemt_me_reconnect_attempts_total 27048
telemt_me_reconnect_success_total 22437
telemt_me_reader_eof_total 23826
telemt_me_idle_close_by_peer_total 23825
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 397115
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 967168
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2032
telemt_desync_full_logged_total 777
telemt_desync_suppressed_total 1255
telemt_desync_frames_bucket_total{bucket="1_2"} 736
telemt_desync_frames_bucket_total{bucket="3_10"} 701
telemt_desync_frames_bucket_total{bucket="gt_10"} 595
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 22819
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 22404
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 382
telemt_user_connections_total{user="hello"} 966430
telemt_user_connections_current{user="hello"} 519
telemt_user_octets_from_client{user="hello"} 11458708176 (10.67 GB)
telemt_user_octets_to_client{user="hello"} 293461697636 (273.31 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 6998.6 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114691
telemt_connections_bad_total 406
telemt_handshake_timeouts_total 675
telemt_upstream_connect_attempt_total 1944
telemt_upstream_connect_success_total 1943
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1944
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1042
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 888
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 1565
telemt_me_reconnect_success_total 1548
telemt_me_reader_eof_total 1577
telemt_me_idle_close_by_peer_total 1577
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 39682
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105876
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 222
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 150
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1565
telemt_me_writer_restored_same_endpoint_total 1524
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 105849
telemt_user_connections_current{user="hello"} 650
telemt_user_octets_from_client{user="hello"} 6421682036 (5.98 GB)
telemt_user_octets_to_client{user="hello"} 35728302148 (33.27 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 92
```