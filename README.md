# Server Metrics 2026-03-13 07:30:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 91904.9 (25h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2520927
telemt_connections_bad_total 36155
telemt_handshake_timeouts_total 26507
telemt_upstream_connect_attempt_total 17930
telemt_upstream_connect_success_total 17830
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 17930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8554
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 1350
telemt_me_reconnect_attempts_total 22115
telemt_me_reconnect_success_total 13243
telemt_me_reader_eof_total 14279
telemt_me_idle_close_by_peer_total 14278
telemt_me_route_drop_no_conn_total 946959
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2312360
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10390
telemt_desync_full_logged_total 2686
telemt_desync_suppressed_total 7704
telemt_desync_frames_bucket_total{bucket="1_2"} 2655
telemt_desync_frames_bucket_total{bucket="3_10"} 3827
telemt_desync_frames_bucket_total{bucket="gt_10"} 3908
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 13707
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 13230
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 2311874
telemt_user_connections_current{user="hello"} 1542
telemt_user_octets_from_client{user="hello"} 33092918724 (30.82 GB)
telemt_user_octets_to_client{user="hello"} 779104495668 (725.60 GB)
telemt_user_unique_ips_current{user="hello"} 422
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 121525.3 (33h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1015215
telemt_connections_bad_total 12891
telemt_handshake_timeouts_total 56844
telemt_upstream_connect_attempt_total 30470
telemt_upstream_connect_success_total 30439
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 30470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3606
telemt_me_reconnect_attempts_total 22895
telemt_me_reconnect_success_total 22775
telemt_me_reader_eof_total 24274
telemt_me_idle_close_by_peer_total 24274
telemt_me_route_drop_no_conn_total 319494
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 904915
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3943
telemt_desync_full_logged_total 1211
telemt_desync_suppressed_total 2732
telemt_desync_frames_bucket_total{bucket="1_2"} 1500
telemt_desync_frames_bucket_total{bucket="3_10"} 1264
telemt_desync_frames_bucket_total{bucket="gt_10"} 1179
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 22998
telemt_me_writer_restored_same_endpoint_total 22766
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 906842
telemt_user_connections_current{user="hello"} 518
telemt_user_octets_from_client{user="hello"} 14013774096 (13.05 GB)
telemt_user_octets_to_client{user="hello"} 341364571159 (317.92 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 121525.3 (33h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2052632
telemt_connections_bad_total 23360
telemt_handshake_timeouts_total 137235
telemt_upstream_connect_attempt_total 27969
telemt_upstream_connect_success_total 27959
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 27969
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13193
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1709
telemt_me_reconnect_attempts_total 22859
telemt_me_reconnect_success_total 21583
telemt_me_reader_eof_total 22860
telemt_me_idle_close_by_peer_total 22859
telemt_me_route_drop_no_conn_total 659811
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1626232
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5513
telemt_desync_full_logged_total 1709
telemt_desync_suppressed_total 3804
telemt_desync_frames_bucket_total{bucket="1_2"} 903
telemt_desync_frames_bucket_total{bucket="3_10"} 2006
telemt_desync_frames_bucket_total{bucket="gt_10"} 2604
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 21792
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 21542
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 1625710
telemt_user_connections_current{user="hello"} 842
telemt_user_octets_from_client{user="hello"} 27197943776 (25.33 GB)
telemt_user_octets_to_client{user="hello"} 588681679329 (548.25 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 121525.8 (33h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1264295
telemt_connections_bad_total 14137
telemt_handshake_timeouts_total 81435
telemt_upstream_connect_attempt_total 40935
telemt_upstream_connect_success_total 38638
telemt_upstream_connect_fail_total 2160
telemt_upstream_connect_attempts_per_request{bucket="1"} 40661
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14920
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2159
telemt_me_keepalive_timeout_total 11434
telemt_me_reconnect_attempts_total 35690
telemt_me_reconnect_success_total 26752
telemt_me_reader_eof_total 28819
telemt_me_idle_close_by_peer_total 28812
telemt_me_route_drop_no_conn_total 455199
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1083273
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2127
telemt_desync_full_logged_total 690
telemt_desync_suppressed_total 1437
telemt_desync_frames_bucket_total{bucket="1_2"} 585
telemt_desync_frames_bucket_total{bucket="3_10"} 819
telemt_desync_frames_bucket_total{bucket="gt_10"} 723
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 27215
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 26728
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 463
telemt_user_connections_total{user="hello"} 1088024
telemt_user_connections_current{user="hello"} 623
telemt_user_octets_from_client{user="hello"} 16533876521 (15.40 GB)
telemt_user_octets_to_client{user="hello"} 431288669134 (401.67 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 121525.3 (33h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1425079
telemt_connections_bad_total 24618
telemt_handshake_timeouts_total 11852
telemt_upstream_connect_attempt_total 38479
telemt_upstream_connect_success_total 38012
telemt_upstream_connect_fail_total 467
telemt_upstream_connect_attempts_per_request{bucket="1"} 38479
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18514
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 185
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 467
telemt_me_keepalive_timeout_total 2093
telemt_me_reconnect_attempts_total 45732
telemt_me_reconnect_success_total 31994
telemt_me_reader_eof_total 33584
telemt_me_idle_close_by_peer_total 33584
telemt_me_seq_mismatch_total 44
telemt_me_route_drop_no_conn_total 523928
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1311010
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 48
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4682
telemt_desync_full_logged_total 1668
telemt_desync_suppressed_total 3014
telemt_desync_frames_bucket_total{bucket="1_2"} 1424
telemt_desync_frames_bucket_total{bucket="3_10"} 1509
telemt_desync_frames_bucket_total{bucket="gt_10"} 1749
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 32773
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 31938
telemt_me_writer_restored_fallback_total 56
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 779
telemt_user_connections_total{user="hello"} 1310819
telemt_user_connections_current{user="hello"} 911
telemt_user_octets_from_client{user="hello"} 16611315392 (15.47 GB)
telemt_user_octets_to_client{user="hello"} 449292385312 (418.44 GB)
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 127
```