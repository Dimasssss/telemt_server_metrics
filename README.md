# Server Metrics 2026-03-14 07:10:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 177131.5 (49h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4993513
telemt_connections_bad_total 40206
telemt_handshake_timeouts_total 113534
telemt_upstream_connect_attempt_total 37107
telemt_upstream_connect_success_total 36864
telemt_upstream_connect_fail_total 243
telemt_upstream_connect_attempts_per_request{bucket="1"} 37107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16694
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 243
telemt_me_keepalive_timeout_total 7338
telemt_me_reconnect_attempts_total 35885
telemt_me_reconnect_success_total 25734
telemt_me_reader_eof_total 27616
telemt_me_idle_close_by_peer_total 27615
telemt_me_route_drop_no_conn_total 1890329
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4580683
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17476
telemt_desync_full_logged_total 4750
telemt_desync_suppressed_total 12726
telemt_desync_frames_bucket_total{bucket="1_2"} 4365
telemt_desync_frames_bucket_total{bucket="3_10"} 6651
telemt_desync_frames_bucket_total{bucket="gt_10"} 6460
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 26420
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 25721
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 686
telemt_user_connections_total{user="hello"} 4582162
telemt_user_connections_current{user="hello"} 1478
telemt_user_octets_from_client{user="hello"} 67140016784 (62.53 GB)
telemt_user_octets_to_client{user="hello"} 1448810318581 (1.32 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 423
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 76795.3 (21h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 837126
telemt_connections_bad_total 53815
telemt_handshake_timeouts_total 15302
telemt_upstream_connect_attempt_total 20764
telemt_upstream_connect_success_total 20492
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 20764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8983
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 234
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_keepalive_timeout_total 2144
telemt_me_reconnect_attempts_total 18095
telemt_me_reconnect_success_total 14629
telemt_me_reader_eof_total 15551
telemt_me_idle_close_by_peer_total 15550
telemt_me_route_drop_no_conn_total 275188
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 668345
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1956
telemt_desync_full_logged_total 598
telemt_desync_suppressed_total 1358
telemt_desync_frames_bucket_total{bucket="1_2"} 411
telemt_desync_frames_bucket_total{bucket="3_10"} 869
telemt_desync_frames_bucket_total{bucket="gt_10"} 676
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 14945
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 14621
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 316
telemt_user_connections_total{user="hello"} 670259
telemt_user_connections_current{user="hello"} 554
telemt_user_octets_from_client{user="hello"} 7017752881 (6.54 GB)
telemt_user_octets_to_client{user="hello"} 228319482612 (212.64 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 206751.0 (57h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3581887
telemt_connections_bad_total 42310
telemt_handshake_timeouts_total 235261
telemt_upstream_connect_attempt_total 46661
telemt_upstream_connect_success_total 46640
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 46661
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24582
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21809
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 242
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10705
telemt_me_reconnect_attempts_total 41031
telemt_me_reconnect_success_total 36055
telemt_me_reader_eof_total 38300
telemt_me_idle_close_by_peer_total 38299
telemt_me_route_drop_no_conn_total 1224828
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2986249
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9828
telemt_desync_full_logged_total 3301
telemt_desync_suppressed_total 6527
telemt_desync_frames_bucket_total{bucket="1_2"} 1713
telemt_desync_frames_bucket_total{bucket="3_10"} 3553
telemt_desync_frames_bucket_total{bucket="gt_10"} 4562
telemt_pool_swap_total 196
telemt_me_writer_removed_unexpected_total 36555
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 36014
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 500
telemt_user_connections_total{user="hello"} 2985398
telemt_user_connections_current{user="hello"} 724
telemt_user_octets_from_client{user="hello"} 50046958272 (46.61 GB)
telemt_user_octets_to_client{user="hello"} 1066656265481 (993.40 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 206753.6 (57h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2385965
telemt_connections_bad_total 23302
telemt_handshake_timeouts_total 285083
telemt_upstream_connect_attempt_total 64383
telemt_upstream_connect_success_total 61894
telemt_upstream_connect_fail_total 2352
telemt_upstream_connect_attempts_per_request{bucket="1"} 64109
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24800
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2351
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20518
telemt_me_reconnect_attempts_total 53644
telemt_me_reconnect_success_total 44598
telemt_me_reader_eof_total 47795
telemt_me_idle_close_by_peer_total 47788
telemt_me_route_drop_no_conn_total 803019
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1880019
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3925
telemt_desync_full_logged_total 1275
telemt_desync_suppressed_total 2650
telemt_desync_frames_bucket_total{bucket="1_2"} 1076
telemt_desync_frames_bucket_total{bucket="3_10"} 1618
telemt_desync_frames_bucket_total{bucket="gt_10"} 1231
telemt_pool_swap_total 183
telemt_me_writer_removed_unexpected_total 45264
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 44574
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 666
telemt_user_connections_total{user="hello"} 1886093
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 28388403183 (26.44 GB)
telemt_user_octets_to_client{user="hello"} 692490656938 (644.93 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 76187.2 (21h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 809187
telemt_connections_bad_total 8265
telemt_handshake_timeouts_total 9502
telemt_upstream_connect_attempt_total 19462
telemt_upstream_connect_success_total 18936
telemt_upstream_connect_fail_total 526
telemt_upstream_connect_attempts_per_request{bucket="1"} 19462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9850
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 526
telemt_me_keepalive_timeout_total 1586
telemt_me_reconnect_attempts_total 60449
telemt_me_reconnect_success_total 15142
telemt_me_reader_eof_total 16924
telemt_me_idle_close_by_peer_total 16923
telemt_me_route_drop_no_conn_total 311725
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 755990
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1843
telemt_desync_full_logged_total 588
telemt_desync_suppressed_total 1255
telemt_desync_frames_bucket_total{bucket="1_2"} 548
telemt_desync_frames_bucket_total{bucket="3_10"} 711
telemt_desync_frames_bucket_total{bucket="gt_10"} 584
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 16686
telemt_me_refill_failed_total 1411
telemt_me_writer_restored_same_endpoint_total 15137
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1544
telemt_user_connections_total{user="hello"} 755851
telemt_user_connections_current{user="hello"} 603
telemt_user_octets_from_client{user="hello"} 13450587552 (12.53 GB)
telemt_user_octets_to_client{user="hello"} 254920775700 (237.41 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 75
```