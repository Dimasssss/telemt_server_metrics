# Server Metrics 2026-03-10 18:19:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 13929.0 (3h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 461605
telemt_connections_bad_total 7985
telemt_handshake_timeouts_total 2186
telemt_upstream_connect_attempt_total 2789
telemt_upstream_connect_success_total 2780
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2789
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1406
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 283
telemt_me_reconnect_attempts_total 11283
telemt_me_reconnect_success_total 2011
telemt_me_reader_eof_total 2279
telemt_me_idle_close_by_peer_total 2279
telemt_me_route_drop_no_conn_total 194486
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 434859
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2191
telemt_desync_full_logged_total 596
telemt_desync_suppressed_total 1595
telemt_desync_frames_bucket_total{bucket="1_2"} 581
telemt_desync_frames_bucket_total{bucket="3_10"} 843
telemt_desync_frames_bucket_total{bucket="gt_10"} 767
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2307
telemt_me_refill_failed_total 289
telemt_me_writer_restored_same_endpoint_total 2005
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 296
telemt_user_connections_total{user="hello"} 434779
telemt_user_connections_current{user="hello"} 1283
telemt_user_octets_from_client{user="hello"} 5722587488 (5.33 GB)
telemt_user_octets_to_client{user="hello"} 126932074044 (118.21 GB)
telemt_user_unique_ips_current{user="hello"} 339
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 13985.7 (3h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176905
telemt_connections_bad_total 1703
telemt_handshake_timeouts_total 12078
telemt_upstream_connect_attempt_total 3202
telemt_upstream_connect_success_total 3187
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 3202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1562
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 2463
telemt_me_reconnect_success_total 2444
telemt_me_reader_eof_total 2545
telemt_me_idle_close_by_peer_total 2545
telemt_me_route_drop_no_conn_total 52941
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153882
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 685
telemt_desync_full_logged_total 209
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 252
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 200
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2461
telemt_me_writer_restored_same_endpoint_total 2423
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 153845
telemt_user_connections_current{user="hello"} 544
telemt_user_octets_from_client{user="hello"} 1908066316 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 41508746864 (38.66 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 13985.5 (3h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 339096
telemt_connections_bad_total 1053
telemt_handshake_timeouts_total 31672
telemt_upstream_connect_attempt_total 4588
telemt_upstream_connect_success_total 4517
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 4588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1759
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 3920
telemt_me_reconnect_success_total 2718
telemt_me_reader_eof_total 2849
telemt_me_idle_close_by_peer_total 2849
telemt_me_route_drop_no_conn_total 111374
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 282687
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 903
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 644
telemt_desync_frames_bucket_total{bucket="1_2"} 227
telemt_desync_frames_bucket_total{bucket="3_10"} 311
telemt_desync_frames_bucket_total{bucket="gt_10"} 365
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2804
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2707
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 283648
telemt_user_connections_current{user="hello"} 809
telemt_user_octets_from_client{user="hello"} 3853225725 (3.59 GB)
telemt_user_octets_to_client{user="hello"} 89607573913 (83.45 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 13986.1 (3h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219395
telemt_connections_bad_total 13638
telemt_handshake_timeouts_total 20280
telemt_upstream_connect_attempt_total 3593
telemt_upstream_connect_success_total 3593
telemt_upstream_connect_attempts_per_request{bucket="1"} 3593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1673
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 2866
telemt_me_reconnect_success_total 2848
telemt_me_reader_eof_total 2963
telemt_me_idle_close_by_peer_total 2963
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 71831
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 176523
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 497
telemt_desync_full_logged_total 197
telemt_desync_suppressed_total 300
telemt_desync_frames_bucket_total{bucket="1_2"} 163
telemt_desync_frames_bucket_total{bucket="3_10"} 182
telemt_desync_frames_bucket_total{bucket="gt_10"} 152
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2874
telemt_me_writer_restored_same_endpoint_total 2836
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 176321
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 2723657984 (2.54 GB)
telemt_user_octets_to_client{user="hello"} 49354009588 (45.96 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 13985.7 (3h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231882
telemt_connections_bad_total 797
telemt_handshake_timeouts_total 1703
telemt_upstream_connect_attempt_total 4262
telemt_upstream_connect_success_total 4250
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 4262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2022
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 85
telemt_me_reconnect_attempts_total 3510
telemt_me_reconnect_success_total 3487
telemt_me_reader_eof_total 3577
telemt_me_idle_close_by_peer_total 3577
telemt_me_route_drop_no_conn_total 85644
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 218345
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1180
telemt_desync_full_logged_total 421
telemt_desync_suppressed_total 759
telemt_desync_frames_bucket_total{bucket="1_2"} 490
telemt_desync_frames_bucket_total{bucket="3_10"} 491
telemt_desync_frames_bucket_total{bucket="gt_10"} 199
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 3524
telemt_me_writer_restored_same_endpoint_total 3487
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 218280
telemt_user_connections_current{user="hello"} 556
telemt_user_octets_from_client{user="hello"} 4809729280 (4.48 GB)
telemt_user_octets_to_client{user="hello"} 68091090868 (63.41 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 75
```