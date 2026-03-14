# Server Metrics 2026-03-14 07:41:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 178971.5 (49h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5053121
telemt_connections_bad_total 40351
telemt_handshake_timeouts_total 115648
telemt_upstream_connect_attempt_total 37603
telemt_upstream_connect_success_total 37359
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 37603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16936
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_keepalive_timeout_total 7353
telemt_me_reconnect_attempts_total 36292
telemt_me_reconnect_success_total 26139
telemt_me_reader_eof_total 28025
telemt_me_idle_close_by_peer_total 28024
telemt_me_route_drop_no_conn_total 1912007
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4633058
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17638
telemt_desync_full_logged_total 4801
telemt_desync_suppressed_total 12837
telemt_desync_frames_bucket_total{bucket="1_2"} 4401
telemt_desync_frames_bucket_total{bucket="3_10"} 6709
telemt_desync_frames_bucket_total{bucket="gt_10"} 6528
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 26830
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 26126
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 691
telemt_user_connections_total{user="hello"} 4634529
telemt_user_connections_current{user="hello"} 1443
telemt_user_octets_from_client{user="hello"} 70751969220 (65.89 GB)
telemt_user_octets_to_client{user="hello"} 1477716571921 (1.34 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 410
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 78635.2 (21h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 859507
telemt_connections_bad_total 53899
telemt_handshake_timeouts_total 15626
telemt_upstream_connect_attempt_total 21159
telemt_upstream_connect_success_total 20885
telemt_upstream_connect_fail_total 274
telemt_upstream_connect_attempts_per_request{bucket="1"} 21159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9194
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 36
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 274
telemt_me_keepalive_timeout_total 2147
telemt_me_reconnect_attempts_total 18402
telemt_me_reconnect_success_total 14936
telemt_me_reader_eof_total 15879
telemt_me_idle_close_by_peer_total 15878
telemt_me_route_drop_no_conn_total 283364
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 689731
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2051
telemt_desync_full_logged_total 635
telemt_desync_suppressed_total 1416
telemt_desync_frames_bucket_total{bucket="1_2"} 428
telemt_desync_frames_bucket_total{bucket="3_10"} 904
telemt_desync_frames_bucket_total{bucket="gt_10"} 719
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 15258
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 14928
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 322
telemt_user_connections_total{user="hello"} 691644
telemt_user_connections_current{user="hello"} 540
telemt_user_octets_from_client{user="hello"} 7224428581 (6.73 GB)
telemt_user_octets_to_client{user="hello"} 238746038036 (222.35 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 208591.9 (57h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3616267
telemt_connections_bad_total 42426
telemt_handshake_timeouts_total 237414
telemt_upstream_connect_attempt_total 47058
telemt_upstream_connect_success_total 47037
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 47058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24810
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21978
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 242
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10710
telemt_me_reconnect_attempts_total 41339
telemt_me_reconnect_success_total 36360
telemt_me_reader_eof_total 38616
telemt_me_idle_close_by_peer_total 38615
telemt_me_route_drop_no_conn_total 1238083
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3017455
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9930
telemt_desync_full_logged_total 3340
telemt_desync_suppressed_total 6590
telemt_desync_frames_bucket_total{bucket="1_2"} 1746
telemt_desync_frames_bucket_total{bucket="3_10"} 3590
telemt_desync_frames_bucket_total{bucket="gt_10"} 4594
telemt_pool_swap_total 197
telemt_me_writer_removed_unexpected_total 36865
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 36319
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 505
telemt_user_connections_total{user="hello"} 3016595
telemt_user_connections_current{user="hello"} 768
telemt_user_octets_from_client{user="hello"} 50390686028 (46.93 GB)
telemt_user_octets_to_client{user="hello"} 1077251129981 (1003.27 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 256
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 208594.6 (57h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2406491
telemt_connections_bad_total 23308
telemt_handshake_timeouts_total 289846
telemt_upstream_connect_attempt_total 65075
telemt_upstream_connect_success_total 62582
telemt_upstream_connect_fail_total 2356
telemt_upstream_connect_attempts_per_request{bucket="1"} 64801
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25054
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2355
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20541
telemt_me_reconnect_attempts_total 54276
telemt_me_reconnect_success_total 45195
telemt_me_reader_eof_total 48428
telemt_me_idle_close_by_peer_total 48421
telemt_me_route_drop_no_conn_total 809453
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1894764
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3928
telemt_desync_full_logged_total 1278
telemt_desync_suppressed_total 2650
telemt_desync_frames_bucket_total{bucket="1_2"} 1079
telemt_desync_frames_bucket_total{bucket="3_10"} 1618
telemt_desync_frames_bucket_total{bucket="gt_10"} 1231
telemt_pool_swap_total 184
telemt_me_writer_removed_unexpected_total 45866
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 45171
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 671
telemt_user_connections_total{user="hello"} 1900865
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 28532160227 (26.57 GB)
telemt_user_octets_to_client{user="hello"} 695613587602 (647.84 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 78028.1 (21h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 831804
telemt_connections_bad_total 8338
telemt_handshake_timeouts_total 9862
telemt_upstream_connect_attempt_total 19937
telemt_upstream_connect_success_total 19403
telemt_upstream_connect_fail_total 534
telemt_upstream_connect_attempts_per_request{bucket="1"} 19937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10093
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 534
telemt_me_keepalive_timeout_total 1590
telemt_me_reconnect_attempts_total 63420
telemt_me_reconnect_success_total 15520
telemt_me_reader_eof_total 17386
telemt_me_idle_close_by_peer_total 17385
telemt_me_route_drop_no_conn_total 320690
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 777280
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1939
telemt_desync_full_logged_total 617
telemt_desync_suppressed_total 1322
telemt_desync_frames_bucket_total{bucket="1_2"} 600
telemt_desync_frames_bucket_total{bucket="3_10"} 738
telemt_desync_frames_bucket_total{bucket="gt_10"} 601
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 17148
telemt_me_refill_failed_total 1492
telemt_me_writer_restored_same_endpoint_total 15515
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1628
telemt_user_connections_total{user="hello"} 777139
telemt_user_connections_current{user="hello"} 694
telemt_user_octets_from_client{user="hello"} 13793234904 (12.85 GB)
telemt_user_octets_to_client{user="hello"} 261594921432 (243.63 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 72
```