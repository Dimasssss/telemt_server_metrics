# Server Metrics 2026-03-13 07:20:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 91292.1 (25h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2494742
telemt_connections_bad_total 36155
telemt_handshake_timeouts_total 26337
telemt_upstream_connect_attempt_total 17843
telemt_upstream_connect_success_total 17743
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 17843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 1349
telemt_me_reconnect_attempts_total 22071
telemt_me_reconnect_success_total 13199
telemt_me_reader_eof_total 14233
telemt_me_idle_close_by_peer_total 14232
telemt_me_route_drop_no_conn_total 938784
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2290227
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10244
telemt_desync_full_logged_total 2648
telemt_desync_suppressed_total 7596
telemt_desync_frames_bucket_total{bucket="1_2"} 2617
telemt_desync_frames_bucket_total{bucket="3_10"} 3769
telemt_desync_frames_bucket_total{bucket="gt_10"} 3858
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 13661
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 13186
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 462
telemt_user_connections_total{user="hello"} 2289749
telemt_user_connections_current{user="hello"} 1477
telemt_user_octets_from_client{user="hello"} 32898554876 (30.64 GB)
telemt_user_octets_to_client{user="hello"} 773701028936 (720.57 GB)
telemt_user_unique_ips_current{user="hello"} 424
telemt_user_unique_ips_recent_window{user="hello"} 238
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 120912.6 (33h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1002345
telemt_connections_bad_total 12784
telemt_handshake_timeouts_total 51651
telemt_upstream_connect_attempt_total 30414
telemt_upstream_connect_success_total 30383
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 30414
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14606
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3606
telemt_me_reconnect_attempts_total 22844
telemt_me_reconnect_success_total 22724
telemt_me_reader_eof_total 24222
telemt_me_idle_close_by_peer_total 24222
telemt_me_route_drop_no_conn_total 316727
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 897679
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3882
telemt_desync_full_logged_total 1194
telemt_desync_suppressed_total 2688
telemt_desync_frames_bucket_total{bucket="1_2"} 1483
telemt_desync_frames_bucket_total{bucket="3_10"} 1245
telemt_desync_frames_bucket_total{bucket="gt_10"} 1154
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 22946
telemt_me_writer_restored_same_endpoint_total 22715
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 899604
telemt_user_connections_current{user="hello"} 606
telemt_user_octets_from_client{user="hello"} 13924363152 (12.97 GB)
telemt_user_octets_to_client{user="hello"} 339464325663 (316.15 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 120912.4 (33h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2040459
telemt_connections_bad_total 23360
telemt_handshake_timeouts_total 136733
telemt_upstream_connect_attempt_total 27887
telemt_upstream_connect_success_total 27877
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 27887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14615
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13149
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1707
telemt_me_reconnect_attempts_total 22780
telemt_me_reconnect_success_total 21504
telemt_me_reader_eof_total 22781
telemt_me_idle_close_by_peer_total 22780
telemt_me_route_drop_no_conn_total 654817
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1614780
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5502
telemt_desync_full_logged_total 1705
telemt_desync_suppressed_total 3797
telemt_desync_frames_bucket_total{bucket="1_2"} 902
telemt_desync_frames_bucket_total{bucket="3_10"} 2000
telemt_desync_frames_bucket_total{bucket="gt_10"} 2600
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 21713
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 21463
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 1614266
telemt_user_connections_current{user="hello"} 884
telemt_user_octets_from_client{user="hello"} 27106367044 (25.24 GB)
telemt_user_octets_to_client{user="hello"} 582931939777 (542.90 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 120913.1 (33h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1251401
telemt_connections_bad_total 14068
telemt_handshake_timeouts_total 81045
telemt_upstream_connect_attempt_total 40860
telemt_upstream_connect_success_total 38563
telemt_upstream_connect_fail_total 2160
telemt_upstream_connect_attempts_per_request{bucket="1"} 40586
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14891
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2159
telemt_me_keepalive_timeout_total 11431
telemt_me_reconnect_attempts_total 35615
telemt_me_reconnect_success_total 26678
telemt_me_reader_eof_total 28743
telemt_me_idle_close_by_peer_total 28736
telemt_me_route_drop_no_conn_total 451729
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1075070
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2108
telemt_desync_full_logged_total 684
telemt_desync_suppressed_total 1424
telemt_desync_frames_bucket_total{bucket="1_2"} 579
telemt_desync_frames_bucket_total{bucket="3_10"} 813
telemt_desync_frames_bucket_total{bucket="gt_10"} 716
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 27139
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 26654
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 461
telemt_user_connections_total{user="hello"} 1079821
telemt_user_connections_current{user="hello"} 635
telemt_user_octets_from_client{user="hello"} 16471298245 (15.34 GB)
telemt_user_octets_to_client{user="hello"} 427823314298 (398.44 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 120912.7 (33h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1412457
telemt_connections_bad_total 23663
telemt_handshake_timeouts_total 11620
telemt_upstream_connect_attempt_total 38431
telemt_upstream_connect_success_total 37964
telemt_upstream_connect_fail_total 467
telemt_upstream_connect_attempts_per_request{bucket="1"} 38431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18487
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 185
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 467
telemt_me_keepalive_timeout_total 2093
telemt_me_reconnect_attempts_total 45684
telemt_me_reconnect_success_total 31946
telemt_me_reader_eof_total 33533
telemt_me_idle_close_by_peer_total 33533
telemt_me_seq_mismatch_total 44
telemt_me_route_drop_no_conn_total 519676
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1300014
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 48
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4654
telemt_desync_full_logged_total 1658
telemt_desync_suppressed_total 2996
telemt_desync_frames_bucket_total{bucket="1_2"} 1409
telemt_desync_frames_bucket_total{bucket="3_10"} 1502
telemt_desync_frames_bucket_total{bucket="gt_10"} 1743
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 32722
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 31890
telemt_me_writer_restored_fallback_total 56
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 776
telemt_user_connections_total{user="hello"} 1299826
telemt_user_connections_current{user="hello"} 771
telemt_user_octets_from_client{user="hello"} 16518329404 (15.38 GB)
telemt_user_octets_to_client{user="hello"} 445597120324 (414.99 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 113
```