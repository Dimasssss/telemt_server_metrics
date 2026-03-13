# Server Metrics 2026-03-13 21:53:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 143687.2 (39h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4501520
telemt_connections_bad_total 38136
telemt_handshake_timeouts_total 106756
telemt_upstream_connect_attempt_total 30017
telemt_upstream_connect_success_total 29809
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 30017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13291
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_keepalive_timeout_total 6622
telemt_me_reconnect_attempts_total 30434
telemt_me_reconnect_success_total 20314
telemt_me_reader_eof_total 21797
telemt_me_idle_close_by_peer_total 21796
telemt_me_route_drop_no_conn_total 1698693
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4124519
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16440
telemt_desync_full_logged_total 4405
telemt_desync_suppressed_total 12035
telemt_desync_frames_bucket_total{bucket="1_2"} 4097
telemt_desync_frames_bucket_total{bucket="3_10"} 6279
telemt_desync_frames_bucket_total{bucket="gt_10"} 6064
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 20924
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 20301
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 610
telemt_user_connections_total{user="hello"} 4126648
telemt_user_connections_current{user="hello"} 883
telemt_user_octets_from_client{user="hello"} 60709265640 (56.54 GB)
telemt_user_octets_to_client{user="hello"} 1306733483869 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 43351.0 (12h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 581396
telemt_connections_bad_total 41512
telemt_handshake_timeouts_total 12359
telemt_upstream_connect_attempt_total 12271
telemt_upstream_connect_success_total 12047
telemt_upstream_connect_fail_total 224
telemt_upstream_connect_attempts_per_request{bucket="1"} 12271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4840
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 199
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 224
telemt_me_keepalive_timeout_total 1902
telemt_me_reconnect_attempts_total 11248
telemt_me_reconnect_success_total 7821
telemt_me_reader_eof_total 8279
telemt_me_idle_close_by_peer_total 8278
telemt_me_route_drop_no_conn_total 212955
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 504523
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
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 8038
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 7813
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 217
telemt_user_connections_total{user="hello"} 506454
telemt_user_connections_current{user="hello"} 298
telemt_user_octets_from_client{user="hello"} 5479906941 (5.10 GB)
telemt_user_octets_to_client{user="hello"} 165458421908 (154.10 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 173307.8 (48h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3274971
telemt_connections_bad_total 31395
telemt_handshake_timeouts_total 219553
telemt_upstream_connect_attempt_total 38444
telemt_upstream_connect_success_total 38423
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 38444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20042
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18158
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10272
telemt_me_reconnect_attempts_total 34420
telemt_me_reconnect_success_total 29470
telemt_me_reader_eof_total 31276
telemt_me_idle_close_by_peer_total 31275
telemt_me_route_drop_no_conn_total 1121217
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2717636
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8927
telemt_desync_full_logged_total 2998
telemt_desync_suppressed_total 5929
telemt_desync_frames_bucket_total{bucket="1_2"} 1470
telemt_desync_frames_bucket_total{bucket="3_10"} 3250
telemt_desync_frames_bucket_total{bucket="gt_10"} 4207
telemt_pool_swap_total 160
telemt_me_writer_removed_unexpected_total 29906
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 29429
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 436
telemt_user_connections_total{user="hello"} 2716901
telemt_user_connections_current{user="hello"} 492
telemt_user_octets_from_client{user="hello"} 44444830360 (41.39 GB)
telemt_user_octets_to_client{user="hello"} 959518628169 (893.62 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 173310.3 (48h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2132685
telemt_connections_bad_total 22813
telemt_handshake_timeouts_total 212217
telemt_upstream_connect_attempt_total 53897
telemt_upstream_connect_success_total 51452
telemt_upstream_connect_fail_total 2308
telemt_upstream_connect_attempts_per_request{bucket="1"} 53623
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20463
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2307
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20304
telemt_me_reconnect_attempts_total 44810
telemt_me_reconnect_success_total 35795
telemt_me_reader_eof_total 38398
telemt_me_idle_close_by_peer_total 38391
telemt_me_route_drop_no_conn_total 750477
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1747888
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3787
telemt_desync_full_logged_total 1211
telemt_desync_suppressed_total 2576
telemt_desync_frames_bucket_total{bucket="1_2"} 999
telemt_desync_frames_bucket_total{bucket="3_10"} 1582
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 151
telemt_me_writer_removed_unexpected_total 36387
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 35771
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 592
telemt_user_connections_total{user="hello"} 1753769
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 27240846199 (25.37 GB)
telemt_user_octets_to_client{user="hello"} 655954038410 (610.90 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 42744.1 (11h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 620689
telemt_connections_bad_total 5845
telemt_handshake_timeouts_total 5698
telemt_upstream_connect_attempt_total 9671
telemt_upstream_connect_success_total 9356
telemt_upstream_connect_fail_total 315
telemt_upstream_connect_attempts_per_request{bucket="1"} 9671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4822
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 315
telemt_me_keepalive_timeout_total 978
telemt_me_reconnect_attempts_total 33105
telemt_me_reconnect_success_total 7203
telemt_me_reader_eof_total 8145
telemt_me_idle_close_by_peer_total 8144
telemt_me_route_drop_no_conn_total 236430
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 581568
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1535
telemt_desync_full_logged_total 481
telemt_desync_suppressed_total 1054
telemt_desync_frames_bucket_total{bucket="1_2"} 466
telemt_desync_frames_bucket_total{bucket="3_10"} 605
telemt_desync_frames_bucket_total{bucket="gt_10"} 464
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 8075
telemt_me_refill_failed_total 806
telemt_me_writer_restored_same_endpoint_total 7198
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 872
telemt_user_connections_total{user="hello"} 581480
telemt_user_connections_current{user="hello"} 384
telemt_user_octets_from_client{user="hello"} 8563449384 (7.98 GB)
telemt_user_octets_to_client{user="hello"} 185832467648 (173.07 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 41
```