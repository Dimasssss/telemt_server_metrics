# Server Metrics 2026-03-11 05:25:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 53916.1 (14h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1049041
telemt_connections_bad_total 11718
telemt_handshake_timeouts_total 36045
telemt_upstream_connect_attempt_total 11486
telemt_upstream_connect_success_total 11477
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 11486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5657
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 544
telemt_me_reconnect_attempts_total 20426
telemt_me_reconnect_success_total 8748
telemt_me_reader_eof_total 9524
telemt_me_idle_close_by_peer_total 9524
telemt_me_route_drop_no_conn_total 388374
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 941874
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4290
telemt_desync_full_logged_total 1218
telemt_desync_suppressed_total 3072
telemt_desync_frames_bucket_total{bucket="1_2"} 1198
telemt_desync_frames_bucket_total{bucket="3_10"} 1613
telemt_desync_frames_bucket_total{bucket="gt_10"} 1479
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 9193
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 8742
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 445
telemt_user_connections_total{user="hello"} 941579
telemt_user_connections_current{user="hello"} 1016
telemt_user_octets_from_client{user="hello"} 12641095800 (11.77 GB)
telemt_user_octets_to_client{user="hello"} 274634878252 (255.77 GB)
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 53972.8 (14h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 406812
telemt_connections_bad_total 2815
telemt_handshake_timeouts_total 19408
telemt_upstream_connect_attempt_total 20009
telemt_upstream_connect_success_total 17104
telemt_upstream_connect_fail_total 2905
telemt_upstream_connect_attempts_per_request{bucket="1"} 20009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7216
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2905
telemt_me_keepalive_timeout_total 1790
telemt_me_reconnect_attempts_total 12281
telemt_me_reconnect_success_total 11461
telemt_me_reader_eof_total 12108
telemt_me_idle_close_by_peer_total 12106
telemt_me_route_drop_no_conn_total 191374
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 350036
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1867
telemt_desync_full_logged_total 559
telemt_desync_suppressed_total 1308
telemt_desync_frames_bucket_total{bucket="1_2"} 586
telemt_desync_frames_bucket_total{bucket="3_10"} 670
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 11595
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 11440
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 352306
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 3371320122 (3.14 GB)
telemt_user_octets_to_client{user="hello"} 86109840224 (80.20 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 53972.7 (14h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 694871
telemt_connections_bad_total 5966
telemt_handshake_timeouts_total 37981
telemt_upstream_connect_attempt_total 14569
telemt_upstream_connect_success_total 14376
telemt_upstream_connect_fail_total 192
telemt_upstream_connect_attempts_per_request{bucket="1"} 14568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6464
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 192
telemt_me_keepalive_timeout_total 571
telemt_me_reconnect_attempts_total 21679
telemt_me_reconnect_success_total 10606
telemt_me_reader_eof_total 11454
telemt_me_idle_close_by_peer_total 11454
telemt_me_route_drop_no_conn_total 234208
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 620239
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1720
telemt_desync_full_logged_total 509
telemt_desync_suppressed_total 1211
telemt_desync_frames_bucket_total{bucket="1_2"} 384
telemt_desync_frames_bucket_total{bucket="3_10"} 605
telemt_desync_frames_bucket_total{bucket="gt_10"} 731
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 11093
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 10595
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 487
telemt_user_connections_total{user="hello"} 621098
telemt_user_connections_current{user="hello"} 460
telemt_user_octets_from_client{user="hello"} 7563057029 (7.04 GB)
telemt_user_octets_to_client{user="hello"} 185549815109 (172.81 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 53973.1 (14h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 529410
telemt_connections_bad_total 50722
telemt_handshake_timeouts_total 55160
telemt_upstream_connect_attempt_total 15456
telemt_upstream_connect_success_total 15456
telemt_upstream_connect_attempts_per_request{bucket="1"} 15456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6776
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 494
telemt_me_reconnect_attempts_total 13805
telemt_me_reconnect_success_total 12762
telemt_me_reader_eof_total 13547
telemt_me_idle_close_by_peer_total 13547
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 156350
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 409035
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 874
telemt_desync_full_logged_total 359
telemt_desync_suppressed_total 515
telemt_desync_frames_bucket_total{bucket="1_2"} 323
telemt_desync_frames_bucket_total{bucket="3_10"} 317
telemt_desync_frames_bucket_total{bucket="gt_10"} 234
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 12909
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 12741
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 408674
telemt_user_connections_current{user="hello"} 421
telemt_user_octets_from_client{user="hello"} 4992039484 (4.65 GB)
telemt_user_octets_to_client{user="hello"} 112125690660 (104.43 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 53972.8 (14h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 553167
telemt_connections_bad_total 5954
telemt_handshake_timeouts_total 3684
telemt_upstream_connect_attempt_total 15409
telemt_upstream_connect_success_total 15345
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 15409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7382
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 563
telemt_me_reconnect_attempts_total 16392
telemt_me_reconnect_success_total 12610
telemt_me_reader_eof_total 13312
telemt_me_idle_close_by_peer_total 13312
telemt_me_route_drop_no_conn_total 180275
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 504912
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2462
telemt_desync_full_logged_total 962
telemt_desync_suppressed_total 1500
telemt_desync_frames_bucket_total{bucket="1_2"} 902
telemt_desync_frames_bucket_total{bucket="3_10"} 1048
telemt_desync_frames_bucket_total{bucket="gt_10"} 512
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 12889
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 12610
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 279
telemt_user_connections_total{user="hello"} 504534
telemt_user_connections_current{user="hello"} 442
telemt_user_octets_from_client{user="hello"} 9072366052 (8.45 GB)
telemt_user_octets_to_client{user="hello"} 177641162804 (165.44 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 63
```