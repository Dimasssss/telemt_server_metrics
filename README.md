# Server Metrics 2026-03-13 23:20:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 148901.6 (41h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4564901
telemt_connections_bad_total 38380
telemt_handshake_timeouts_total 107653
telemt_upstream_connect_attempt_total 31240
telemt_upstream_connect_success_total 31026
telemt_upstream_connect_fail_total 214
telemt_upstream_connect_attempts_per_request{bucket="1"} 31240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17042
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13839
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 214
telemt_me_keepalive_timeout_total 6648
telemt_me_reconnect_attempts_total 31389
telemt_me_reconnect_success_total 21260
telemt_me_reader_eof_total 22795
telemt_me_idle_close_by_peer_total 22794
telemt_me_route_drop_no_conn_total 1725857
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4182813
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16594
telemt_desync_full_logged_total 4468
telemt_desync_suppressed_total 12126
telemt_desync_frames_bucket_total{bucket="1_2"} 4131
telemt_desync_frames_bucket_total{bucket="3_10"} 6348
telemt_desync_frames_bucket_total{bucket="gt_10"} 6115
telemt_pool_swap_total 126
telemt_me_writer_removed_unexpected_total 21883
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 21247
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 623
telemt_user_connections_total{user="hello"} 4184737
telemt_user_connections_current{user="hello"} 587
telemt_user_octets_from_client{user="hello"} 61406747012 (57.19 GB)
telemt_user_octets_to_client{user="hello"} 1323811974429 (1.20 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 48565.3 (13h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 607618
telemt_connections_bad_total 44798
telemt_handshake_timeouts_total 12554
telemt_upstream_connect_attempt_total 13731
telemt_upstream_connect_success_total 13495
telemt_upstream_connect_fail_total 236
telemt_upstream_connect_attempts_per_request{bucket="1"} 13731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 236
telemt_me_keepalive_timeout_total 1922
telemt_me_reconnect_attempts_total 12479
telemt_me_reconnect_success_total 9043
telemt_me_reader_eof_total 9583
telemt_me_idle_close_by_peer_total 9582
telemt_me_route_drop_no_conn_total 220365
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 523904
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
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 9284
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 9035
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 525849
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 5787961045 (5.39 GB)
telemt_user_octets_to_client{user="hello"} 171443630072 (159.67 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 178521.9 (49h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3311858
telemt_connections_bad_total 31941
telemt_handshake_timeouts_total 221640
telemt_upstream_connect_attempt_total 39653
telemt_upstream_connect_success_total 39632
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 39653
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18716
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10335
telemt_me_reconnect_attempts_total 35367
telemt_me_reconnect_success_total 30412
telemt_me_reader_eof_total 32284
telemt_me_idle_close_by_peer_total 32283
telemt_me_route_drop_no_conn_total 1135943
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2751442
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9026
telemt_desync_full_logged_total 3035
telemt_desync_suppressed_total 5991
telemt_desync_frames_bucket_total{bucket="1_2"} 1519
telemt_desync_frames_bucket_total{bucket="3_10"} 3269
telemt_desync_frames_bucket_total{bucket="gt_10"} 4238
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 30859
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 30371
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 447
telemt_user_connections_total{user="hello"} 2750694
telemt_user_connections_current{user="hello"} 376
telemt_user_octets_from_client{user="hello"} 44736407856 (41.66 GB)
telemt_user_octets_to_client{user="hello"} 972966387529 (906.15 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 178524.6 (49h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2177197
telemt_connections_bad_total 22851
telemt_handshake_timeouts_total 228293
telemt_upstream_connect_attempt_total 55630
telemt_upstream_connect_success_total 53178
telemt_upstream_connect_fail_total 2315
telemt_upstream_connect_attempts_per_request{bucket="1"} 55356
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21132
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2314
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20351
telemt_me_reconnect_attempts_total 46275
telemt_me_reconnect_success_total 37255
telemt_me_reader_eof_total 39962
telemt_me_idle_close_by_peer_total 39955
telemt_me_route_drop_no_conn_total 759663
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1767002
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3795
telemt_desync_full_logged_total 1216
telemt_desync_suppressed_total 2579
telemt_desync_frames_bucket_total{bucket="1_2"} 1002
telemt_desync_frames_bucket_total{bucket="3_10"} 1587
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 37856
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 37231
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 601
telemt_user_connections_total{user="hello"} 1772890
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 27336138355 (25.46 GB)
telemt_user_octets_to_client{user="hello"} 661107267042 (615.70 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 47958.0 (13h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 653763
telemt_connections_bad_total 7853
telemt_handshake_timeouts_total 7215
telemt_upstream_connect_attempt_total 11134
telemt_upstream_connect_success_total 10788
telemt_upstream_connect_fail_total 346
telemt_upstream_connect_attempts_per_request{bucket="1"} 11134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5598
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 346
telemt_me_keepalive_timeout_total 1441
telemt_me_reconnect_attempts_total 38084
telemt_me_reconnect_success_total 8364
telemt_me_reader_eof_total 9442
telemt_me_idle_close_by_peer_total 9441
telemt_me_route_drop_no_conn_total 248069
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 609109
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1605
telemt_desync_full_logged_total 505
telemt_desync_suppressed_total 1100
telemt_desync_frames_bucket_total{bucket="1_2"} 487
telemt_desync_frames_bucket_total{bucket="3_10"} 626
telemt_desync_frames_bucket_total{bucket="gt_10"} 492
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 9368
telemt_me_refill_failed_total 925
telemt_me_writer_restored_same_endpoint_total 8359
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1004
telemt_user_connections_total{user="hello"} 609012
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 9720440224 (9.05 GB)
telemt_user_octets_to_client{user="hello"} 199777656944 (186.06 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 31
```