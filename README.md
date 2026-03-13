# Server Metrics 2026-03-13 22:34:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 146141.5 (40h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4533979
telemt_connections_bad_total 38370
telemt_handshake_timeouts_total 107090
telemt_upstream_connect_attempt_total 30517
telemt_upstream_connect_success_total 30308
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 30517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13528
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_timeout_total 6640
telemt_me_reconnect_attempts_total 30804
telemt_me_reconnect_success_total 20680
telemt_me_reader_eof_total 22194
telemt_me_idle_close_by_peer_total 22193
telemt_me_route_drop_no_conn_total 1712054
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4154015
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16550
telemt_desync_full_logged_total 4452
telemt_desync_suppressed_total 12098
telemt_desync_frames_bucket_total{bucket="1_2"} 4118
telemt_desync_frames_bucket_total{bucket="3_10"} 6331
telemt_desync_frames_bucket_total{bucket="gt_10"} 6101
telemt_pool_swap_total 125
telemt_me_writer_removed_unexpected_total 21297
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 20667
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 617
telemt_user_connections_total{user="hello"} 4156147
telemt_user_connections_current{user="hello"} 646
telemt_user_octets_from_client{user="hello"} 61050904176 (56.86 GB)
telemt_user_octets_to_client{user="hello"} 1312921052153 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 45805.2 (12h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 593882
telemt_connections_bad_total 42931
telemt_handshake_timeouts_total 12447
telemt_upstream_connect_attempt_total 12857
telemt_upstream_connect_success_total 12630
telemt_upstream_connect_fail_total 227
telemt_upstream_connect_attempts_per_request{bucket="1"} 12857
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5103
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 227
telemt_me_keepalive_timeout_total 1911
telemt_me_reconnect_attempts_total 11743
telemt_me_reconnect_success_total 8312
telemt_me_reader_eof_total 8806
telemt_me_idle_close_by_peer_total 8805
telemt_me_route_drop_no_conn_total 216609
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 513792
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
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 8539
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 8304
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 515721
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 5696231153 (5.31 GB)
telemt_user_octets_to_client{user="hello"} 168059328724 (156.52 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 175761.9 (48h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3293857
telemt_connections_bad_total 31802
telemt_handshake_timeouts_total 220108
telemt_upstream_connect_attempt_total 38976
telemt_upstream_connect_success_total 38955
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 38976
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18425
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10298
telemt_me_reconnect_attempts_total 34822
telemt_me_reconnect_success_total 29870
telemt_me_reader_eof_total 31705
telemt_me_idle_close_by_peer_total 31704
telemt_me_route_drop_no_conn_total 1129150
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2735372
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8993
telemt_desync_full_logged_total 3027
telemt_desync_suppressed_total 5966
telemt_desync_frames_bucket_total{bucket="1_2"} 1512
telemt_desync_frames_bucket_total{bucket="3_10"} 3258
telemt_desync_frames_bucket_total{bucket="gt_10"} 4223
telemt_pool_swap_total 163
telemt_me_writer_removed_unexpected_total 30311
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 29829
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 441
telemt_user_connections_total{user="hello"} 2734631
telemt_user_connections_current{user="hello"} 409
telemt_user_octets_from_client{user="hello"} 44634860164 (41.57 GB)
telemt_user_octets_to_client{user="hello"} 967563519257 (901.11 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 175764.5 (48h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2155707
telemt_connections_bad_total 22837
telemt_handshake_timeouts_total 220556
telemt_upstream_connect_attempt_total 54704
telemt_upstream_connect_success_total 52255
telemt_upstream_connect_fail_total 2312
telemt_upstream_connect_attempts_per_request{bucket="1"} 54430
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20764
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2311
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20328
telemt_me_reconnect_attempts_total 45481
telemt_me_reconnect_success_total 36463
telemt_me_reader_eof_total 39110
telemt_me_idle_close_by_peer_total 39103
telemt_me_route_drop_no_conn_total 755632
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1757651
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
telemt_me_writer_removed_unexpected_total 37059
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 36439
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 596
telemt_user_connections_total{user="hello"} 1763534
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 27300086131 (25.43 GB)
telemt_user_octets_to_client{user="hello"} 658453852206 (613.23 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 45198.1 (12h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 637655
telemt_connections_bad_total 7086
telemt_handshake_timeouts_total 6203
telemt_upstream_connect_attempt_total 10277
telemt_upstream_connect_success_total 9945
telemt_upstream_connect_fail_total 332
telemt_upstream_connect_attempts_per_request{bucket="1"} 10277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5152
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 332
telemt_me_keepalive_timeout_total 1429
telemt_me_reconnect_attempts_total 37115
telemt_me_reconnect_success_total 7655
telemt_me_reader_eof_total 8709
telemt_me_idle_close_by_peer_total 8708
telemt_me_route_drop_no_conn_total 242477
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 595729
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1588
telemt_desync_full_logged_total 495
telemt_desync_suppressed_total 1093
telemt_desync_frames_bucket_total{bucket="1_2"} 481
telemt_desync_frames_bucket_total{bucket="3_10"} 620
telemt_desync_frames_bucket_total{bucket="gt_10"} 487
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 8647
telemt_me_refill_failed_total 917
telemt_me_writer_restored_same_endpoint_total 7650
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 992
telemt_user_connections_total{user="hello"} 595637
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 9008655216 (8.39 GB)
telemt_user_octets_to_client{user="hello"} 194054333856 (180.73 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 36
```