# Server Metrics 2026-03-14 05:02:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 169452.8 (47h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4799322
telemt_connections_bad_total 39902
telemt_handshake_timeouts_total 110150
telemt_upstream_connect_attempt_total 35736
telemt_upstream_connect_success_total 35501
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 35736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16022
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_timeout_total 7304
telemt_me_reconnect_attempts_total 34868
telemt_me_reconnect_success_total 24723
telemt_me_reader_eof_total 26536
telemt_me_idle_close_by_peer_total 26535
telemt_me_route_drop_no_conn_total 1817916
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4402987
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16963
telemt_desync_full_logged_total 4587
telemt_desync_suppressed_total 12376
telemt_desync_frames_bucket_total{bucket="1_2"} 4231
telemt_desync_frames_bucket_total{bucket="3_10"} 6474
telemt_desync_frames_bucket_total{bucket="gt_10"} 6258
telemt_pool_swap_total 148
telemt_me_writer_removed_unexpected_total 25390
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 24710
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 667
telemt_user_connections_total{user="hello"} 4404540
telemt_user_connections_current{user="hello"} 938
telemt_user_octets_from_client{user="hello"} 64317117428 (59.90 GB)
telemt_user_octets_to_client{user="hello"} 1387881081761 (1.26 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 321
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 69116.2 (19h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 755282
telemt_connections_bad_total 52959
telemt_handshake_timeouts_total 13815
telemt_upstream_connect_attempt_total 18996
telemt_upstream_connect_success_total 18732
telemt_upstream_connect_fail_total 264
telemt_upstream_connect_attempts_per_request{bucket="1"} 18996
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8116
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 264
telemt_me_keepalive_timeout_total 2107
telemt_me_reconnect_attempts_total 16724
telemt_me_reconnect_success_total 13268
telemt_me_reader_eof_total 14093
telemt_me_idle_close_by_peer_total 14092
telemt_me_route_drop_no_conn_total 248821
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 598986
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1784
telemt_desync_full_logged_total 528
telemt_desync_suppressed_total 1256
telemt_desync_frames_bucket_total{bucket="1_2"} 373
telemt_desync_frames_bucket_total{bucket="3_10"} 795
telemt_desync_frames_bucket_total{bucket="gt_10"} 616
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 13557
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 13260
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 289
telemt_user_connections_total{user="hello"} 600937
telemt_user_connections_current{user="hello"} 307
telemt_user_octets_from_client{user="hello"} 6418798429 (5.98 GB)
telemt_user_octets_to_client{user="hello"} 199616395640 (185.91 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 199072.9 (55h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3452200
telemt_connections_bad_total 37323
telemt_handshake_timeouts_total 228298
telemt_upstream_connect_attempt_total 45034
telemt_upstream_connect_success_total 45013
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 45034
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21066
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10611
telemt_me_reconnect_attempts_total 39754
telemt_me_reconnect_success_total 34784
telemt_me_reader_eof_total 36955
telemt_me_idle_close_by_peer_total 36954
telemt_me_route_drop_no_conn_total 1180308
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2876608
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9533
telemt_desync_full_logged_total 3202
telemt_desync_suppressed_total 6331
telemt_desync_frames_bucket_total{bucket="1_2"} 1650
telemt_desync_frames_bucket_total{bucket="3_10"} 3455
telemt_desync_frames_bucket_total{bucket="gt_10"} 4428
telemt_pool_swap_total 189
telemt_me_writer_removed_unexpected_total 35267
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 34743
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 483
telemt_user_connections_total{user="hello"} 2875822
telemt_user_connections_current{user="hello"} 526
telemt_user_octets_from_client{user="hello"} 45892477012 (42.74 GB)
telemt_user_octets_to_client{user="hello"} 1031193935001 (960.37 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 199075.5 (55h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2314975
telemt_connections_bad_total 23100
telemt_handshake_timeouts_total 262697
telemt_upstream_connect_attempt_total 62213
telemt_upstream_connect_success_total 59736
telemt_upstream_connect_fail_total 2340
telemt_upstream_connect_attempts_per_request{bucket="1"} 61939
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23896
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2339
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20470
telemt_me_reconnect_attempts_total 51835
telemt_me_reconnect_success_total 42795
telemt_me_reader_eof_total 45901
telemt_me_idle_close_by_peer_total 45894
telemt_me_route_drop_no_conn_total 784687
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1835079
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3884
telemt_desync_full_logged_total 1251
telemt_desync_suppressed_total 2633
telemt_desync_frames_bucket_total{bucket="1_2"} 1045
telemt_desync_frames_bucket_total{bucket="3_10"} 1614
telemt_desync_frames_bucket_total{bucket="gt_10"} 1225
telemt_pool_swap_total 177
telemt_me_writer_removed_unexpected_total 43448
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 42771
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 653
telemt_user_connections_total{user="hello"} 1841049
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 27895922711 (25.98 GB)
telemt_user_octets_to_client{user="hello"} 675337802090 (628.96 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 68509.2 (19h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 741658
telemt_connections_bad_total 7996
telemt_handshake_timeouts_total 8910
telemt_upstream_connect_attempt_total 17702
telemt_upstream_connect_success_total 17234
telemt_upstream_connect_fail_total 468
telemt_upstream_connect_attempts_per_request{bucket="1"} 17702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9072
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 468
telemt_me_keepalive_timeout_total 1539
telemt_me_reconnect_attempts_total 52558
telemt_me_reconnect_success_total 13796
telemt_me_reader_eof_total 15356
telemt_me_idle_close_by_peer_total 15355
telemt_me_route_drop_no_conn_total 283162
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 692174
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1745
telemt_desync_full_logged_total 553
telemt_desync_suppressed_total 1192
telemt_desync_frames_bucket_total{bucket="1_2"} 518
telemt_desync_frames_bucket_total{bucket="3_10"} 682
telemt_desync_frames_bucket_total{bucket="gt_10"} 545
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 15126
telemt_me_refill_failed_total 1207
telemt_me_writer_restored_same_endpoint_total 13791
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1330
telemt_user_connections_total{user="hello"} 692040
telemt_user_connections_current{user="hello"} 455
telemt_user_octets_from_client{user="hello"} 12493483704 (11.64 GB)
telemt_user_octets_to_client{user="hello"} 225761250640 (210.26 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 58
```