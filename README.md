# Server Metrics 2026-03-13 07:35:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 92211.3 (25h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2533310
telemt_connections_bad_total 36155
telemt_handshake_timeouts_total 26555
telemt_upstream_connect_attempt_total 17983
telemt_upstream_connect_success_total 17883
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 17983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8581
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 1351
telemt_me_reconnect_attempts_total 22168
telemt_me_reconnect_success_total 13295
telemt_me_reader_eof_total 14336
telemt_me_idle_close_by_peer_total 14335
telemt_me_route_drop_no_conn_total 951417
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2323638
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10490
telemt_desync_full_logged_total 2704
telemt_desync_suppressed_total 7786
telemt_desync_frames_bucket_total{bucket="1_2"} 2681
telemt_desync_frames_bucket_total{bucket="3_10"} 3872
telemt_desync_frames_bucket_total{bucket="gt_10"} 3937
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 13760
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 13282
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 465
telemt_user_connections_total{user="hello"} 2323146
telemt_user_connections_current{user="hello"} 1749
telemt_user_octets_from_client{user="hello"} 33197692276 (30.92 GB)
telemt_user_octets_to_client{user="hello"} 781541868896 (727.87 GB)
telemt_user_unique_ips_current{user="hello"} 457
telemt_user_unique_ips_recent_window{user="hello"} 256
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 121831.8 (33h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1027646
telemt_connections_bad_total 12991
telemt_handshake_timeouts_total 65571
telemt_upstream_connect_attempt_total 30567
telemt_upstream_connect_success_total 30536
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 30567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14682
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3607
telemt_me_reconnect_attempts_total 22953
telemt_me_reconnect_success_total 22833
telemt_me_reader_eof_total 24337
telemt_me_idle_close_by_peer_total 24337
telemt_me_route_drop_no_conn_total 321106
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 908655
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3965
telemt_desync_full_logged_total 1218
telemt_desync_suppressed_total 2747
telemt_desync_frames_bucket_total{bucket="1_2"} 1504
telemt_desync_frames_bucket_total{bucket="3_10"} 1271
telemt_desync_frames_bucket_total{bucket="gt_10"} 1190
telemt_pool_swap_total 125
telemt_me_writer_removed_unexpected_total 23056
telemt_me_writer_restored_same_endpoint_total 22824
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 910582
telemt_user_connections_current{user="hello"} 570
telemt_user_octets_from_client{user="hello"} 14044187804 (13.08 GB)
telemt_user_octets_to_client{user="hello"} 342480227019 (318.96 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 121831.7 (33h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2059095
telemt_connections_bad_total 23366
telemt_handshake_timeouts_total 137667
telemt_upstream_connect_attempt_total 28076
telemt_upstream_connect_success_total 28066
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 28076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13242
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1723
telemt_me_reconnect_attempts_total 22926
telemt_me_reconnect_success_total 21650
telemt_me_reader_eof_total 22936
telemt_me_idle_close_by_peer_total 22935
telemt_me_route_drop_no_conn_total 662469
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1632081
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5523
telemt_desync_full_logged_total 1712
telemt_desync_suppressed_total 3811
telemt_desync_frames_bucket_total{bucket="1_2"} 906
telemt_desync_frames_bucket_total{bucket="3_10"} 2010
telemt_desync_frames_bucket_total{bucket="gt_10"} 2607
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 21859
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 21609
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 1631559
telemt_user_connections_current{user="hello"} 943
telemt_user_octets_from_client{user="hello"} 27247845212 (25.38 GB)
telemt_user_octets_to_client{user="hello"} 591649271169 (551.02 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 121832.1 (33h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1270468
telemt_connections_bad_total 14137
telemt_handshake_timeouts_total 81573
telemt_upstream_connect_attempt_total 41044
telemt_upstream_connect_success_total 38747
telemt_upstream_connect_fail_total 2160
telemt_upstream_connect_attempts_per_request{bucket="1"} 40770
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14969
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2159
telemt_me_keepalive_timeout_total 11434
telemt_me_reconnect_attempts_total 35756
telemt_me_reconnect_success_total 26818
telemt_me_reader_eof_total 28896
telemt_me_idle_close_by_peer_total 28889
telemt_me_route_drop_no_conn_total 456950
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1087232
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2132
telemt_desync_full_logged_total 693
telemt_desync_suppressed_total 1439
telemt_desync_frames_bucket_total{bucket="1_2"} 586
telemt_desync_frames_bucket_total{bucket="3_10"} 820
telemt_desync_frames_bucket_total{bucket="gt_10"} 726
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 27283
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 26794
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 465
telemt_user_connections_total{user="hello"} 1091977
telemt_user_connections_current{user="hello"} 615
telemt_user_octets_from_client{user="hello"} 16604454737 (15.46 GB)
telemt_user_octets_to_client{user="hello"} 432361149290 (402.67 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 121832.0 (33h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1431124
telemt_connections_bad_total 25090
telemt_handshake_timeouts_total 11902
telemt_upstream_connect_attempt_total 38595
telemt_upstream_connect_success_total 38124
telemt_upstream_connect_fail_total 471
telemt_upstream_connect_attempts_per_request{bucket="1"} 38595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18561
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 471
telemt_me_keepalive_timeout_total 2094
telemt_me_reconnect_attempts_total 45801
telemt_me_reconnect_success_total 32062
telemt_me_reader_eof_total 33659
telemt_me_idle_close_by_peer_total 33659
telemt_me_seq_mismatch_total 44
telemt_me_route_drop_no_conn_total 526078
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1316315
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 48
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4691
telemt_desync_full_logged_total 1671
telemt_desync_suppressed_total 3020
telemt_desync_frames_bucket_total{bucket="1_2"} 1428
telemt_desync_frames_bucket_total{bucket="3_10"} 1512
telemt_desync_frames_bucket_total{bucket="gt_10"} 1751
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 32842
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 32006
telemt_me_writer_restored_fallback_total 56
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 780
telemt_user_connections_total{user="hello"} 1316124
telemt_user_connections_current{user="hello"} 882
telemt_user_octets_from_client{user="hello"} 16657809708 (15.51 GB)
telemt_user_octets_to_client{user="hello"} 450863131340 (419.90 GB)
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 119
```