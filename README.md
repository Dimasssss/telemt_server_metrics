# Server Metrics 2026-03-13 22:13:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 144914.4 (40h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4518618
telemt_connections_bad_total 38365
telemt_handshake_timeouts_total 106949
telemt_upstream_connect_attempt_total 30230
telemt_upstream_connect_success_total 30022
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 30230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13403
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_keepalive_timeout_total 6632
telemt_me_reconnect_attempts_total 30604
telemt_me_reconnect_success_total 20484
telemt_me_reader_eof_total 21979
telemt_me_idle_close_by_peer_total 21978
telemt_me_route_drop_no_conn_total 1706020
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4140143
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16503
telemt_desync_full_logged_total 4430
telemt_desync_suppressed_total 12073
telemt_desync_frames_bucket_total{bucket="1_2"} 4104
telemt_desync_frames_bucket_total{bucket="3_10"} 6309
telemt_desync_frames_bucket_total{bucket="gt_10"} 6090
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 21097
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 20471
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 613
telemt_user_connections_total{user="hello"} 4142273
telemt_user_connections_current{user="hello"} 725
telemt_user_octets_from_client{user="hello"} 60927048552 (56.74 GB)
telemt_user_octets_to_client{user="hello"} 1309958512633 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 44578.1 (12h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 588553
telemt_connections_bad_total 42917
telemt_handshake_timeouts_total 12402
telemt_upstream_connect_attempt_total 12594
telemt_upstream_connect_success_total 12369
telemt_upstream_connect_fail_total 225
telemt_upstream_connect_attempts_per_request{bucket="1"} 12594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4981
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 225
telemt_me_keepalive_timeout_total 1905
telemt_me_reconnect_attempts_total 11525
telemt_me_reconnect_success_total 8096
telemt_me_reader_eof_total 8577
telemt_me_idle_close_by_peer_total 8576
telemt_me_route_drop_no_conn_total 214884
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 509371
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
telemt_me_writer_removed_unexpected_total 8319
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 8088
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 511300
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 5551205369 (5.17 GB)
telemt_user_octets_to_client{user="hello"} 166751930712 (155.30 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 174534.9 (48h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3284936
telemt_connections_bad_total 31455
telemt_handshake_timeouts_total 219764
telemt_upstream_connect_attempt_total 38660
telemt_upstream_connect_success_total 38639
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 38660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18263
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10281
telemt_me_reconnect_attempts_total 34593
telemt_me_reconnect_success_total 29642
telemt_me_reader_eof_total 31457
telemt_me_idle_close_by_peer_total 31456
telemt_me_route_drop_no_conn_total 1125319
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2727222
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8967
telemt_desync_full_logged_total 3014
telemt_desync_suppressed_total 5953
telemt_desync_frames_bucket_total{bucket="1_2"} 1495
telemt_desync_frames_bucket_total{bucket="3_10"} 3255
telemt_desync_frames_bucket_total{bucket="gt_10"} 4217
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 30079
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 29601
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 437
telemt_user_connections_total{user="hello"} 2726487
telemt_user_connections_current{user="hello"} 405
telemt_user_octets_from_client{user="hello"} 44558876992 (41.50 GB)
telemt_user_octets_to_client{user="hello"} 964845571745 (898.58 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 174537.5 (48h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2144476
telemt_connections_bad_total 22828
telemt_handshake_timeouts_total 216491
telemt_upstream_connect_attempt_total 54280
telemt_upstream_connect_success_total 51833
telemt_upstream_connect_fail_total 2310
telemt_upstream_connect_attempts_per_request{bucket="1"} 54006
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20586
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2309
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20319
telemt_me_reconnect_attempts_total 45147
telemt_me_reconnect_success_total 36131
telemt_me_reader_eof_total 38763
telemt_me_idle_close_by_peer_total 38756
telemt_me_route_drop_no_conn_total 753051
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1752851
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
telemt_pool_swap_total 152
telemt_me_writer_removed_unexpected_total 36725
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 36107
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 594
telemt_user_connections_total{user="hello"} 1758732
telemt_user_connections_current{user="hello"} 245
telemt_user_octets_from_client{user="hello"} 27273797379 (25.40 GB)
telemt_user_octets_to_client{user="hello"} 657501206038 (612.35 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 43971.4 (12h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 629167
telemt_connections_bad_total 6075
telemt_handshake_timeouts_total 5858
telemt_upstream_connect_attempt_total 9977
telemt_upstream_connect_success_total 9656
telemt_upstream_connect_fail_total 321
telemt_upstream_connect_attempts_per_request{bucket="1"} 9977
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4991
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 321
telemt_me_keepalive_timeout_total 1427
telemt_me_reconnect_attempts_total 34610
telemt_me_reconnect_success_total 7455
telemt_me_reader_eof_total 8435
telemt_me_idle_close_by_peer_total 8434
telemt_me_route_drop_no_conn_total 239863
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 589129
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1573
telemt_desync_full_logged_total 490
telemt_desync_suppressed_total 1083
telemt_desync_frames_bucket_total{bucket="1_2"} 479
telemt_desync_frames_bucket_total{bucket="3_10"} 614
telemt_desync_frames_bucket_total{bucket="gt_10"} 480
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 8373
telemt_me_refill_failed_total 845
telemt_me_writer_restored_same_endpoint_total 7450
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 918
telemt_user_connections_total{user="hello"} 589040
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 8683189192 (8.09 GB)
telemt_user_octets_to_client{user="hello"} 188005255420 (175.09 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 39
```