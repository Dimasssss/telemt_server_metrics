# Server Metrics 2026-03-13 09:17:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 98336.7 (27h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2793692
telemt_connections_bad_total 36388
telemt_handshake_timeouts_total 39101
telemt_upstream_connect_attempt_total 19365
telemt_upstream_connect_success_total 19257
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 19365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9927
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9281
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_keepalive_timeout_total 1394
telemt_me_reconnect_attempts_total 24421
telemt_me_reconnect_success_total 14360
telemt_me_reader_eof_total 15484
telemt_me_idle_close_by_peer_total 15483
telemt_me_route_drop_no_conn_total 1037584
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2553545
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11273
telemt_desync_full_logged_total 2918
telemt_desync_suppressed_total 8355
telemt_desync_frames_bucket_total{bucket="1_2"} 2898
telemt_desync_frames_bucket_total{bucket="3_10"} 4219
telemt_desync_frames_bucket_total{bucket="gt_10"} 4156
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 14871
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 14347
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 511
telemt_user_connections_total{user="hello"} 2553145
telemt_user_connections_current{user="hello"} 1748
telemt_user_octets_from_client{user="hello"} 35701021804 (33.25 GB)
telemt_user_octets_to_client{user="hello"} 837030451224 (779.55 GB)
telemt_user_unique_ips_current{user="hello"} 443
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 127956.8 (35h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1144785
telemt_connections_bad_total 14292
telemt_handshake_timeouts_total 105742
telemt_upstream_connect_attempt_total 31786
telemt_upstream_connect_success_total 31755
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 31786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15282
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3665
telemt_me_reconnect_attempts_total 23865
telemt_me_reconnect_success_total 23740
telemt_me_reader_eof_total 25309
telemt_me_idle_close_by_peer_total 25309
telemt_me_route_drop_no_conn_total 350855
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 983327
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4343
telemt_desync_full_logged_total 1318
telemt_desync_suppressed_total 3025
telemt_desync_frames_bucket_total{bucket="1_2"} 1585
telemt_desync_frames_bucket_total{bucket="3_10"} 1430
telemt_desync_frames_bucket_total{bucket="gt_10"} 1328
telemt_pool_swap_total 132
telemt_me_writer_removed_unexpected_total 23974
telemt_me_writer_restored_same_endpoint_total 23731
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 985254
telemt_user_connections_current{user="hello"} 576
telemt_user_octets_from_client{user="hello"} 15009180056 (13.98 GB)
telemt_user_octets_to_client{user="hello"} 361920317335 (337.06 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 127956.9 (35h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2198869
telemt_connections_bad_total 24639
telemt_handshake_timeouts_total 146476
telemt_upstream_connect_attempt_total 29352
telemt_upstream_connect_success_total 29342
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 29352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13859
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1806
telemt_me_reconnect_attempts_total 23893
telemt_me_reconnect_success_total 22608
telemt_me_reader_eof_total 23947
telemt_me_idle_close_by_peer_total 23946
telemt_me_route_drop_no_conn_total 715326
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1757417
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5841
telemt_desync_full_logged_total 1859
telemt_desync_suppressed_total 3982
telemt_desync_frames_bucket_total{bucket="1_2"} 954
telemt_desync_frames_bucket_total{bucket="3_10"} 2132
telemt_desync_frames_bucket_total{bucket="gt_10"} 2755
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 22832
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 22567
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 224
telemt_user_connections_total{user="hello"} 1756850
telemt_user_connections_current{user="hello"} 938
telemt_user_octets_from_client{user="hello"} 30698070468 (28.59 GB)
telemt_user_octets_to_client{user="hello"} 635276616585 (591.65 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 278
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 127957.3 (35h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1395251
telemt_connections_bad_total 14228
telemt_handshake_timeouts_total 85574
telemt_upstream_connect_attempt_total 42319
telemt_upstream_connect_success_total 40014
telemt_upstream_connect_fail_total 2168
telemt_upstream_connect_attempts_per_request{bucket="1"} 42045
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15547
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2167
telemt_me_keepalive_timeout_total 11463
telemt_me_reconnect_attempts_total 36718
telemt_me_reconnect_success_total 27776
telemt_me_reader_eof_total 29914
telemt_me_idle_close_by_peer_total 29907
telemt_me_route_drop_no_conn_total 490437
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1163358
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2200
telemt_desync_full_logged_total 720
telemt_desync_suppressed_total 1480
telemt_desync_frames_bucket_total{bucket="1_2"} 604
telemt_desync_frames_bucket_total{bucket="3_10"} 848
telemt_desync_frames_bucket_total{bucket="gt_10"} 748
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 28254
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 27752
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 478
telemt_user_connections_total{user="hello"} 1168122
telemt_user_connections_current{user="hello"} 686
telemt_user_octets_from_client{user="hello"} 17584682673 (16.38 GB)
telemt_user_octets_to_client{user="hello"} 464153580062 (432.28 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 127957.0 (35h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1551710
telemt_connections_bad_total 34499
telemt_handshake_timeouts_total 12721
telemt_upstream_connect_attempt_total 40928
telemt_upstream_connect_success_total 40437
telemt_upstream_connect_fail_total 491
telemt_upstream_connect_attempts_per_request{bucket="1"} 40928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20405
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19823
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 491
telemt_me_keepalive_timeout_total 2203
telemt_me_reconnect_attempts_total 48380
telemt_me_reconnect_success_total 34054
telemt_me_reader_eof_total 35692
telemt_me_idle_close_by_peer_total 35692
telemt_me_seq_mismatch_total 48
telemt_me_route_drop_no_conn_total 567427
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1416915
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 52
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4950
telemt_desync_full_logged_total 1767
telemt_desync_suppressed_total 3183
telemt_desync_frames_bucket_total{bucket="1_2"} 1517
telemt_desync_frames_bucket_total{bucket="3_10"} 1602
telemt_desync_frames_bucket_total{bucket="gt_10"} 1831
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 34876
telemt_me_refill_failed_total 443
telemt_me_writer_restored_same_endpoint_total 33993
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 822
telemt_user_connections_total{user="hello"} 1416716
telemt_user_connections_current{user="hello"} 874
telemt_user_octets_from_client{user="hello"} 18247008428 (16.99 GB)
telemt_user_octets_to_client{user="hello"} 491129547856 (457.40 GB)
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 118
```