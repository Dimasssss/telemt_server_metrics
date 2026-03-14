# Server Metrics 2026-03-14 00:47:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 154115.7 (42h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4610802
telemt_connections_bad_total 38454
telemt_handshake_timeouts_total 107892
telemt_upstream_connect_attempt_total 32487
telemt_upstream_connect_success_total 32269
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 32487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 6669
telemt_me_reconnect_attempts_total 32369
telemt_me_reconnect_success_total 22237
telemt_me_reader_eof_total 23845
telemt_me_idle_close_by_peer_total 23844
telemt_me_route_drop_no_conn_total 1745895
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4227056
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16648
telemt_desync_full_logged_total 4489
telemt_desync_suppressed_total 12159
telemt_desync_frames_bucket_total{bucket="1_2"} 4148
telemt_desync_frames_bucket_total{bucket="3_10"} 6362
telemt_desync_frames_bucket_total{bucket="gt_10"} 6138
telemt_pool_swap_total 131
telemt_me_writer_removed_unexpected_total 22873
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 22224
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 636
telemt_user_connections_total{user="hello"} 4228931
telemt_user_connections_current{user="hello"} 508
telemt_user_octets_from_client{user="hello"} 62378839740 (58.09 GB)
telemt_user_octets_to_client{user="hello"} 1336741023885 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 53779.2 (14h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 655689
telemt_connections_bad_total 48961
telemt_handshake_timeouts_total 12873
telemt_upstream_connect_attempt_total 15084
telemt_upstream_connect_success_total 14839
telemt_upstream_connect_fail_total 245
telemt_upstream_connect_attempts_per_request{bucket="1"} 15084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6228
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 245
telemt_me_keepalive_timeout_total 1944
telemt_me_reconnect_attempts_total 13564
telemt_me_reconnect_success_total 10122
telemt_me_reader_eof_total 10738
telemt_me_idle_close_by_peer_total 10737
telemt_me_route_drop_no_conn_total 227283
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 538619
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1645
telemt_desync_full_logged_total 446
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 714
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 10370
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 10114
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 248
telemt_user_connections_total{user="hello"} 540570
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 5863039585 (5.46 GB)
telemt_user_octets_to_client{user="hello"} 175491037044 (163.44 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 183735.9 (51h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3341182
telemt_connections_bad_total 34172
telemt_handshake_timeouts_total 222481
telemt_upstream_connect_attempt_total 41128
telemt_upstream_connect_success_total 41107
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 41128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19331
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10357
telemt_me_reconnect_attempts_total 36582
telemt_me_reconnect_success_total 31626
telemt_me_reader_eof_total 33574
telemt_me_idle_close_by_peer_total 33573
telemt_me_route_drop_no_conn_total 1146819
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2777012
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9141
telemt_desync_full_logged_total 3070
telemt_desync_suppressed_total 6071
telemt_desync_frames_bucket_total{bucket="1_2"} 1538
telemt_desync_frames_bucket_total{bucket="3_10"} 3313
telemt_desync_frames_bucket_total{bucket="gt_10"} 4290
telemt_pool_swap_total 172
telemt_me_writer_removed_unexpected_total 32081
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 31585
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 455
telemt_user_connections_total{user="hello"} 2776251
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 44902204828 (41.82 GB)
telemt_user_octets_to_client{user="hello"} 985998116541 (918.28 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 183738.5 (51h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2217428
telemt_connections_bad_total 22917
telemt_handshake_timeouts_total 238554
telemt_upstream_connect_attempt_total 57184
telemt_upstream_connect_success_total 54726
telemt_upstream_connect_fail_total 2321
telemt_upstream_connect_attempts_per_request{bucket="1"} 56910
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2320
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20384
telemt_me_reconnect_attempts_total 47565
telemt_me_reconnect_success_total 38539
telemt_me_reader_eof_total 41341
telemt_me_idle_close_by_peer_total 41334
telemt_me_route_drop_no_conn_total 765700
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1782767
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3800
telemt_desync_full_logged_total 1220
telemt_desync_suppressed_total 2580
telemt_desync_frames_bucket_total{bucket="1_2"} 1006
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 162
telemt_me_writer_removed_unexpected_total 39153
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 38515
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 614
telemt_user_connections_total{user="hello"} 1788682
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 27394612763 (25.51 GB)
telemt_user_octets_to_client{user="hello"} 663469881586 (617.90 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 53172.4 (14h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 676689
telemt_connections_bad_total 7870
telemt_handshake_timeouts_total 8607
telemt_upstream_connect_attempt_total 12996
telemt_upstream_connect_success_total 12626
telemt_upstream_connect_fail_total 370
telemt_upstream_connect_attempts_per_request{bucket="1"} 12996
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6486
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 370
telemt_me_keepalive_timeout_total 1464
telemt_me_reconnect_attempts_total 42107
telemt_me_reconnect_success_total 9950
telemt_me_reader_eof_total 11154
telemt_me_idle_close_by_peer_total 11153
telemt_me_route_drop_no_conn_total 255066
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 629321
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1638
telemt_desync_full_logged_total 513
telemt_desync_suppressed_total 1125
telemt_desync_frames_bucket_total{bucket="1_2"} 492
telemt_desync_frames_bucket_total{bucket="3_10"} 641
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 11043
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 9945
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1093
telemt_user_connections_total{user="hello"} 629220
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 10541228184 (9.82 GB)
telemt_user_octets_to_client{user="hello"} 206835070996 (192.63 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 27
```