# Server Metrics 2026-03-13 22:19:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 145221.1 (40h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4522345
telemt_connections_bad_total 38365
telemt_handshake_timeouts_total 107022
telemt_upstream_connect_attempt_total 30339
telemt_upstream_connect_success_total 30131
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 30339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13450
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_keepalive_timeout_total 6640
telemt_me_reconnect_attempts_total 30670
telemt_me_reconnect_success_total 20550
telemt_me_reader_eof_total 22053
telemt_me_idle_close_by_peer_total 22052
telemt_me_route_drop_no_conn_total 1707604
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4143503
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16509
telemt_desync_full_logged_total 4434
telemt_desync_suppressed_total 12075
telemt_desync_frames_bucket_total{bucket="1_2"} 4108
telemt_desync_frames_bucket_total{bucket="3_10"} 6310
telemt_desync_frames_bucket_total{bucket="gt_10"} 6091
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 21163
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 20537
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 613
telemt_user_connections_total{user="hello"} 4145633
telemt_user_connections_current{user="hello"} 647
telemt_user_octets_from_client{user="hello"} 60950748800 (56.76 GB)
telemt_user_octets_to_client{user="hello"} 1310452511841 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 44884.9 (12h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 589936
telemt_connections_bad_total 42917
telemt_handshake_timeouts_total 12426
telemt_upstream_connect_attempt_total 12645
telemt_upstream_connect_success_total 12420
telemt_upstream_connect_fail_total 225
telemt_upstream_connect_attempts_per_request{bucket="1"} 12645
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5008
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 225
telemt_me_keepalive_timeout_total 1908
telemt_me_reconnect_attempts_total 11576
telemt_me_reconnect_success_total 8147
telemt_me_reader_eof_total 8630
telemt_me_idle_close_by_peer_total 8629
telemt_me_route_drop_no_conn_total 215408
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 510502
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1643
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 712
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 8372
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 8139
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 225
telemt_user_connections_total{user="hello"} 512431
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 5567883581 (5.19 GB)
telemt_user_octets_to_client{user="hello"} 167039012628 (155.57 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 174841.7 (48h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3287613
telemt_connections_bad_total 31524
telemt_handshake_timeouts_total 219898
telemt_upstream_connect_attempt_total 38775
telemt_upstream_connect_success_total 38754
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 38775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18313
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10287
telemt_me_reconnect_attempts_total 34665
telemt_me_reconnect_success_total 29712
telemt_me_reader_eof_total 31538
telemt_me_idle_close_by_peer_total 31537
telemt_me_route_drop_no_conn_total 1126346
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2729666
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8977
telemt_desync_full_logged_total 3018
telemt_desync_suppressed_total 5959
telemt_desync_frames_bucket_total{bucket="1_2"} 1504
telemt_desync_frames_bucket_total{bucket="3_10"} 3255
telemt_desync_frames_bucket_total{bucket="gt_10"} 4218
telemt_pool_swap_total 162
telemt_me_writer_removed_unexpected_total 30152
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 29671
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 440
telemt_user_connections_total{user="hello"} 2728928
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 44574399568 (41.51 GB)
telemt_user_octets_to_client{user="hello"} 965707085465 (899.38 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 174844.0 (48h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2147098
telemt_connections_bad_total 22829
telemt_handshake_timeouts_total 217555
telemt_upstream_connect_attempt_total 54397
telemt_upstream_connect_success_total 51948
telemt_upstream_connect_fail_total 2312
telemt_upstream_connect_attempts_per_request{bucket="1"} 54123
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20628
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2311
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20319
telemt_me_reconnect_attempts_total 45219
telemt_me_reconnect_success_total 36203
telemt_me_reader_eof_total 38848
telemt_me_idle_close_by_peer_total 38841
telemt_me_route_drop_no_conn_total 753709
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1753990
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3794
telemt_desync_full_logged_total 1215
telemt_desync_suppressed_total 2579
telemt_desync_frames_bucket_total{bucket="1_2"} 1002
telemt_desync_frames_bucket_total{bucket="3_10"} 1586
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 153
telemt_me_writer_removed_unexpected_total 36797
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 36179
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 594
telemt_user_connections_total{user="hello"} 1759871
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 27277933895 (25.40 GB)
telemt_user_octets_to_client{user="hello"} 657744315990 (612.57 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 44277.9 (12h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 631338
telemt_connections_bad_total 6426
telemt_handshake_timeouts_total 5913
telemt_upstream_connect_attempt_total 10077
telemt_upstream_connect_success_total 9751
telemt_upstream_connect_fail_total 326
telemt_upstream_connect_attempts_per_request{bucket="1"} 10077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4686
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5040
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 326
telemt_me_keepalive_timeout_total 1427
telemt_me_reconnect_attempts_total 35364
telemt_me_reconnect_success_total 7505
telemt_me_reader_eof_total 8507
telemt_me_idle_close_by_peer_total 8506
telemt_me_route_drop_no_conn_total 240454
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 590766
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1575
telemt_desync_full_logged_total 491
telemt_desync_suppressed_total 1084
telemt_desync_frames_bucket_total{bucket="1_2"} 479
telemt_desync_frames_bucket_total{bucket="3_10"} 614
telemt_desync_frames_bucket_total{bucket="gt_10"} 482
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 8445
telemt_me_refill_failed_total 867
telemt_me_writer_restored_same_endpoint_total 7500
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 940
telemt_user_connections_total{user="hello"} 590677
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 8926644056 (8.31 GB)
telemt_user_octets_to_client{user="hello"} 189355889124 (176.35 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 44
```