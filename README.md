# Server Metrics 2026-03-14 07:26:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 178050.9 (49h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5021477
telemt_connections_bad_total 40350
telemt_handshake_timeouts_total 114648
telemt_upstream_connect_attempt_total 37322
telemt_upstream_connect_success_total 37079
telemt_upstream_connect_fail_total 243
telemt_upstream_connect_attempts_per_request{bucket="1"} 37322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16799
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 243
telemt_me_keepalive_timeout_total 7345
telemt_me_reconnect_attempts_total 36056
telemt_me_reconnect_success_total 25904
telemt_me_reader_eof_total 27788
telemt_me_idle_close_by_peer_total 27787
telemt_me_route_drop_no_conn_total 1900557
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4606543
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17519
telemt_desync_full_logged_total 4768
telemt_desync_suppressed_total 12751
telemt_desync_frames_bucket_total{bucket="1_2"} 4372
telemt_desync_frames_bucket_total{bucket="3_10"} 6666
telemt_desync_frames_bucket_total{bucket="gt_10"} 6481
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 26592
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 25891
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 688
telemt_user_connections_total{user="hello"} 4608025
telemt_user_connections_current{user="hello"} 1458
telemt_user_octets_from_client{user="hello"} 68974483092 (64.24 GB)
telemt_user_octets_to_client{user="hello"} 1461635947277 (1.33 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 419
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 77714.7 (21h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 847793
telemt_connections_bad_total 53895
telemt_handshake_timeouts_total 15433
telemt_upstream_connect_attempt_total 20960
telemt_upstream_connect_success_total 20687
telemt_upstream_connect_fail_total 273
telemt_upstream_connect_attempts_per_request{bucket="1"} 20960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9085
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 238
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 273
telemt_me_keepalive_timeout_total 2145
telemt_me_reconnect_attempts_total 18247
telemt_me_reconnect_success_total 14781
telemt_me_reader_eof_total 15712
telemt_me_idle_close_by_peer_total 15711
telemt_me_route_drop_no_conn_total 278864
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 678474
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1988
telemt_desync_full_logged_total 613
telemt_desync_suppressed_total 1375
telemt_desync_frames_bucket_total{bucket="1_2"} 416
telemt_desync_frames_bucket_total{bucket="3_10"} 880
telemt_desync_frames_bucket_total{bucket="gt_10"} 692
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 15098
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 14773
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 317
telemt_user_connections_total{user="hello"} 680388
telemt_user_connections_current{user="hello"} 519
telemt_user_octets_from_client{user="hello"} 7140485613 (6.65 GB)
telemt_user_octets_to_client{user="hello"} 233604035624 (217.56 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 207671.4 (57h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3599626
telemt_connections_bad_total 42318
telemt_handshake_timeouts_total 236278
telemt_upstream_connect_attempt_total 46844
telemt_upstream_connect_success_total 46823
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 46844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21900
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 242
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10710
telemt_me_reconnect_attempts_total 41171
telemt_me_reconnect_success_total 36194
telemt_me_reader_eof_total 38446
telemt_me_idle_close_by_peer_total 38445
telemt_me_route_drop_no_conn_total 1231722
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3002445
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9879
telemt_desync_full_logged_total 3323
telemt_desync_suppressed_total 6556
telemt_desync_frames_bucket_total{bucket="1_2"} 1728
telemt_desync_frames_bucket_total{bucket="3_10"} 3572
telemt_desync_frames_bucket_total{bucket="gt_10"} 4579
telemt_pool_swap_total 197
telemt_me_writer_removed_unexpected_total 36695
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 36153
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 501
telemt_user_connections_total{user="hello"} 3001600
telemt_user_connections_current{user="hello"} 719
telemt_user_octets_from_client{user="hello"} 50185448780 (46.74 GB)
telemt_user_octets_to_client{user="hello"} 1072345059677 (998.70 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 207674.0 (57h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2396170
telemt_connections_bad_total 23306
telemt_handshake_timeouts_total 287476
telemt_upstream_connect_attempt_total 64776
telemt_upstream_connect_success_total 62285
telemt_upstream_connect_fail_total 2354
telemt_upstream_connect_attempts_per_request{bucket="1"} 64502
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24946
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2353
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20525
telemt_me_reconnect_attempts_total 54022
telemt_me_reconnect_success_total 44942
telemt_me_reader_eof_total 48142
telemt_me_idle_close_by_peer_total 48135
telemt_me_route_drop_no_conn_total 805965
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1887357
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3927
telemt_desync_full_logged_total 1277
telemt_desync_suppressed_total 2650
telemt_desync_frames_bucket_total{bucket="1_2"} 1078
telemt_desync_frames_bucket_total{bucket="3_10"} 1618
telemt_desync_frames_bucket_total{bucket="gt_10"} 1231
telemt_pool_swap_total 183
telemt_me_writer_removed_unexpected_total 45611
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 44918
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 669
telemt_user_connections_total{user="hello"} 1893444
telemt_user_connections_current{user="hello"} 359
telemt_user_octets_from_client{user="hello"} 28442142499 (26.49 GB)
telemt_user_octets_to_client{user="hello"} 694079911990 (646.41 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 77108.0 (21h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 819593
telemt_connections_bad_total 8330
telemt_handshake_timeouts_total 9664
telemt_upstream_connect_attempt_total 19721
telemt_upstream_connect_success_total 19192
telemt_upstream_connect_fail_total 529
telemt_upstream_connect_attempts_per_request{bucket="1"} 19721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9983
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 529
telemt_me_keepalive_timeout_total 1587
telemt_me_reconnect_attempts_total 61972
telemt_me_reconnect_success_total 15352
telemt_me_reader_eof_total 17175
telemt_me_idle_close_by_peer_total 17174
telemt_me_route_drop_no_conn_total 315856
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 765742
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1897
telemt_desync_full_logged_total 599
telemt_desync_suppressed_total 1298
telemt_desync_frames_bucket_total{bucket="1_2"} 580
telemt_desync_frames_bucket_total{bucket="3_10"} 723
telemt_desync_frames_bucket_total{bucket="gt_10"} 594
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 16937
telemt_me_refill_failed_total 1452
telemt_me_writer_restored_same_endpoint_total 15347
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1585
telemt_user_connections_total{user="hello"} 765601
telemt_user_connections_current{user="hello"} 624
telemt_user_octets_from_client{user="hello"} 13604307932 (12.67 GB)
telemt_user_octets_to_client{user="hello"} 258005895904 (240.29 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 79
```