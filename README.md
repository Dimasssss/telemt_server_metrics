# Server Metrics 2026-03-13 10:29:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 102626.2 (28h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2974034
telemt_connections_bad_total 36442
telemt_handshake_timeouts_total 53959
telemt_upstream_connect_attempt_total 20168
telemt_upstream_connect_success_total 20059
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 20168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9698
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 1446
telemt_me_reconnect_attempts_total 25042
telemt_me_reconnect_success_total 14973
telemt_me_reader_eof_total 16124
telemt_me_idle_close_by_peer_total 16123
telemt_me_route_drop_no_conn_total 1097324
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2712584
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11852
telemt_desync_full_logged_total 3053
telemt_desync_suppressed_total 8799
telemt_desync_frames_bucket_total{bucket="1_2"} 3029
telemt_desync_frames_bucket_total{bucket="3_10"} 4452
telemt_desync_frames_bucket_total{bucket="gt_10"} 4371
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 15495
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 14960
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 522
telemt_user_connections_total{user="hello"} 2712523
telemt_user_connections_current{user="hello"} 1723
telemt_user_octets_from_client{user="hello"} 37267196108 (34.71 GB)
telemt_user_octets_to_client{user="hello"} 880025623680 (819.59 GB)
telemt_user_unique_ips_current{user="hello"} 465
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 2290.0 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20368
telemt_connections_bad_total 1882
telemt_handshake_timeouts_total 349
telemt_upstream_connect_attempt_total 553
telemt_upstream_connect_success_total 485
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 269
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 393
telemt_me_reconnect_success_total 327
telemt_me_reader_eof_total 314
telemt_me_idle_close_by_peer_total 314
telemt_me_route_drop_no_conn_total 6671
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17669
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 47
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 321
telemt_me_writer_restored_same_endpoint_total 320
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_user_connections_total{user="hello"} 17670
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 260648056 (248.57 MB)
telemt_user_octets_to_client{user="hello"} 3581837228 (3.34 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 132246.6 (36h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2304102
telemt_connections_bad_total 25093
telemt_handshake_timeouts_total 157007
telemt_upstream_connect_attempt_total 30165
telemt_upstream_connect_success_total 30155
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 30165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14241
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1879
telemt_me_reconnect_attempts_total 24530
telemt_me_reconnect_success_total 23240
telemt_me_reader_eof_total 24620
telemt_me_idle_close_by_peer_total 24619
telemt_me_route_drop_no_conn_total 754696
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1849270
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6074
telemt_desync_full_logged_total 1942
telemt_desync_suppressed_total 4132
telemt_desync_frames_bucket_total{bucket="1_2"} 989
telemt_desync_frames_bucket_total{bucket="3_10"} 2209
telemt_desync_frames_bucket_total{bucket="gt_10"} 2876
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 23474
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 23199
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 1848711
telemt_user_connections_current{user="hello"} 1038
telemt_user_octets_from_client{user="hello"} 31886897488 (29.70 GB)
telemt_user_octets_to_client{user="hello"} 666546231845 (620.77 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 132247.1 (36h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1455307
telemt_connections_bad_total 14238
telemt_handshake_timeouts_total 90322
telemt_upstream_connect_attempt_total 43168
telemt_upstream_connect_success_total 40858
telemt_upstream_connect_fail_total 2173
telemt_upstream_connect_attempts_per_request{bucket="1"} 42894
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15932
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2172
telemt_me_keepalive_timeout_total 11507
telemt_me_reconnect_attempts_total 37389
telemt_me_reconnect_success_total 28438
telemt_me_reader_eof_total 30613
telemt_me_idle_close_by_peer_total 30606
telemt_me_route_drop_no_conn_total 515299
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1217582
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2296
telemt_desync_full_logged_total 760
telemt_desync_suppressed_total 1536
telemt_desync_frames_bucket_total{bucket="1_2"} 638
telemt_desync_frames_bucket_total{bucket="3_10"} 876
telemt_desync_frames_bucket_total{bucket="gt_10"} 782
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 28924
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 28414
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 486
telemt_user_connections_total{user="hello"} 1222319
telemt_user_connections_current{user="hello"} 648
telemt_user_octets_from_client{user="hello"} 18492896761 (17.22 GB)
telemt_user_octets_to_client{user="hello"} 485470155222 (452.13 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 1682.4 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13274
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 448
telemt_upstream_connect_success_total 443
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 250
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 332
telemt_me_reconnect_success_total 326
telemt_me_reader_eof_total 287
telemt_me_idle_close_by_peer_total 287
telemt_me_route_drop_no_conn_total 3690
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12500
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 78
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_me_writer_removed_unexpected_total 308
telemt_me_writer_restored_same_endpoint_total 323
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 12
telemt_user_connections_total{user="hello"} 12500
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 167869904 (160.09 MB)
telemt_user_octets_to_client{user="hello"} 6472611544 (6.03 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 91
```