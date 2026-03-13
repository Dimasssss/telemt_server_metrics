# Server Metrics 2026-03-13 05:33:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 84861.9 (23h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2283624
telemt_connections_bad_total 33795
telemt_handshake_timeouts_total 24014
telemt_upstream_connect_attempt_total 16715
telemt_upstream_connect_success_total 16622
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 16715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 1309
telemt_me_reconnect_attempts_total 21252
telemt_me_reconnect_success_total 12385
telemt_me_reader_eof_total 13364
telemt_me_idle_close_by_peer_total 13363
telemt_me_route_drop_no_conn_total 868812
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2100305
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9305
telemt_desync_full_logged_total 2398
telemt_desync_suppressed_total 6907
telemt_desync_frames_bucket_total{bucket="1_2"} 2426
telemt_desync_frames_bucket_total{bucket="3_10"} 3391
telemt_desync_frames_bucket_total{bucket="gt_10"} 3488
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 12833
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 12372
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 448
telemt_user_connections_total{user="hello"} 2099665
telemt_user_connections_current{user="hello"} 1162
telemt_user_octets_from_client{user="hello"} 30438753792 (28.35 GB)
telemt_user_octets_to_client{user="hello"} 721666583772 (672.10 GB)
telemt_user_unique_ips_current{user="hello"} 340
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 114482.2 (31h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 926188
telemt_connections_bad_total 12379
telemt_handshake_timeouts_total 40435
telemt_upstream_connect_attempt_total 28972
telemt_upstream_connect_success_total 28941
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 28972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13898
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3539
telemt_me_reconnect_attempts_total 21706
telemt_me_reconnect_success_total 21589
telemt_me_reader_eof_total 23022
telemt_me_idle_close_by_peer_total 23022
telemt_me_route_drop_no_conn_total 294944
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 835085
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3322
telemt_desync_full_logged_total 1046
telemt_desync_suppressed_total 2276
telemt_desync_frames_bucket_total{bucket="1_2"} 1315
telemt_desync_frames_bucket_total{bucket="3_10"} 1087
telemt_desync_frames_bucket_total{bucket="gt_10"} 920
telemt_pool_swap_total 118
telemt_me_writer_removed_unexpected_total 21802
telemt_me_writer_restored_same_endpoint_total 21580
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 213
telemt_user_connections_total{user="hello"} 836979
telemt_user_connections_current{user="hello"} 419
telemt_user_octets_from_client{user="hello"} 13309171488 (12.40 GB)
telemt_user_octets_to_client{user="hello"} 319553310067 (297.61 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 114482.2 (31h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1911439
telemt_connections_bad_total 20597
telemt_handshake_timeouts_total 125548
telemt_upstream_connect_attempt_total 26645
telemt_upstream_connect_success_total 26635
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 26645
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12553
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1646
telemt_me_reconnect_attempts_total 21844
telemt_me_reconnect_success_total 20573
telemt_me_reader_eof_total 21795
telemt_me_idle_close_by_peer_total 21794
telemt_me_route_drop_no_conn_total 614273
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1506621
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5250
telemt_desync_full_logged_total 1598
telemt_desync_suppressed_total 3652
telemt_desync_frames_bucket_total{bucket="1_2"} 868
telemt_desync_frames_bucket_total{bucket="3_10"} 1898
telemt_desync_frames_bucket_total{bucket="gt_10"} 2484
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 20770
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 20532
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 197
telemt_user_connections_total{user="hello"} 1506118
telemt_user_connections_current{user="hello"} 665
telemt_user_octets_from_client{user="hello"} 25921595564 (24.14 GB)
telemt_user_octets_to_client{user="hello"} 536478023457 (499.63 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 114482.6 (31h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1172290
telemt_connections_bad_total 13982
telemt_handshake_timeouts_total 76154
telemt_upstream_connect_attempt_total 39096
telemt_upstream_connect_success_total 36809
telemt_upstream_connect_fail_total 2150
telemt_upstream_connect_attempts_per_request{bucket="1"} 38822
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14053
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2149
telemt_me_keepalive_timeout_total 11398
telemt_me_reconnect_attempts_total 34166
telemt_me_reconnect_success_total 25232
telemt_me_reader_eof_total 27220
telemt_me_idle_close_by_peer_total 27213
telemt_me_route_drop_no_conn_total 417363
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1009318
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1982
telemt_desync_full_logged_total 652
telemt_desync_suppressed_total 1330
telemt_desync_frames_bucket_total{bucket="1_2"} 550
telemt_desync_frames_bucket_total{bucket="3_10"} 770
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 25683
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 25208
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 451
telemt_user_connections_total{user="hello"} 1014501
telemt_user_connections_current{user="hello"} 437
telemt_user_octets_from_client{user="hello"} 15439210945 (14.38 GB)
telemt_user_octets_to_client{user="hello"} 403803204618 (376.07 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 114482.4 (31h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1313333
telemt_connections_bad_total 13543
telemt_handshake_timeouts_total 10774
telemt_upstream_connect_attempt_total 36152
telemt_upstream_connect_success_total 35717
telemt_upstream_connect_fail_total 435
telemt_upstream_connect_attempts_per_request{bucket="1"} 36152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17316
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 435
telemt_me_keepalive_timeout_total 1963
telemt_me_reconnect_attempts_total 43740
telemt_me_reconnect_success_total 30006
telemt_me_reader_eof_total 31533
telemt_me_idle_close_by_peer_total 31533
telemt_me_seq_mismatch_total 40
telemt_me_route_drop_no_conn_total 485648
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1215548
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 44
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4398
telemt_desync_full_logged_total 1581
telemt_desync_suppressed_total 2817
telemt_desync_frames_bucket_total{bucket="1_2"} 1336
telemt_desync_frames_bucket_total{bucket="3_10"} 1428
telemt_desync_frames_bucket_total{bucket="gt_10"} 1634
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 30769
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 29954
telemt_me_writer_restored_fallback_total 52
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 763
telemt_user_connections_total{user="hello"} 1215401
telemt_user_connections_current{user="hello"} 548
telemt_user_octets_from_client{user="hello"} 14702044028 (13.69 GB)
telemt_user_octets_to_client{user="hello"} 412125178124 (383.82 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 83
```