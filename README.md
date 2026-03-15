# Server Metrics 2026-03-15 07:00:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 31588.8 (8h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 533065
telemt_connections_bad_total 12865
telemt_handshake_timeouts_total 3704
telemt_upstream_connect_attempt_total 6638
telemt_upstream_connect_success_total 6612
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 6638
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3494
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 5045
telemt_me_reconnect_success_total 5019
telemt_me_reader_eof_total 5301
telemt_me_idle_close_by_peer_total 5301
telemt_me_route_drop_no_conn_total 163053
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 450077
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1182
telemt_desync_full_logged_total 372
telemt_desync_suppressed_total 810
telemt_desync_frames_bucket_total{bucket="1_2"} 244
telemt_desync_frames_bucket_total{bucket="3_10"} 441
telemt_desync_frames_bucket_total{bucket="gt_10"} 497
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 5081
telemt_me_writer_restored_same_endpoint_total 5008
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 450087
telemt_user_connections_current{user="hello"} 1655
telemt_user_octets_from_client{user="hello"} 5372186400 (5.00 GB)
telemt_user_octets_to_client{user="hello"} 158891009852 (147.98 GB)
telemt_user_unique_ips_current{user="hello"} 493
telemt_user_unique_ips_recent_window{user="hello"} 245
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 31589.2 (8h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191406
telemt_connections_bad_total 18330
telemt_handshake_timeouts_total 5789
telemt_upstream_connect_attempt_total 8904
telemt_upstream_connect_success_total 8858
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 8904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3994
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 6980
telemt_me_reconnect_success_total 6942
telemt_me_reader_eof_total 7337
telemt_me_idle_close_by_peer_total 7337
telemt_me_route_drop_no_conn_total 49221
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161349
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 537
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 350
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 217
telemt_desync_frames_bucket_total{bucket="gt_10"} 176
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 6970
telemt_me_writer_restored_same_endpoint_total 6934
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 161641
telemt_user_connections_current{user="hello"} 589
telemt_user_octets_from_client{user="hello"} 2591063535 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 59498626360 (55.41 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 31589.6 (8h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 351050
telemt_connections_bad_total 10039
telemt_handshake_timeouts_total 31942
telemt_upstream_connect_attempt_total 7247
telemt_upstream_connect_success_total 7215
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 7247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3367
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 5640
telemt_me_reconnect_success_total 5609
telemt_me_reader_eof_total 5935
telemt_me_idle_close_by_peer_total 5935
telemt_me_route_drop_no_conn_total 90645
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 291572
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 573
telemt_desync_full_logged_total 237
telemt_desync_suppressed_total 336
telemt_desync_frames_bucket_total{bucket="1_2"} 128
telemt_desync_frames_bucket_total{bucket="3_10"} 202
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 5671
telemt_me_writer_restored_same_endpoint_total 5590
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 291368
telemt_user_connections_current{user="hello"} 863
telemt_user_octets_from_client{user="hello"} 4549098180 (4.24 GB)
telemt_user_octets_to_client{user="hello"} 122693795596 (114.27 GB)
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 31589.3 (8h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239766
telemt_connections_bad_total 43763
telemt_handshake_timeouts_total 15220
telemt_upstream_connect_attempt_total 10565
telemt_upstream_connect_success_total 10323
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 10565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5426
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 18627
telemt_me_reconnect_success_total 8728
telemt_me_reader_eof_total 9312
telemt_me_idle_close_by_peer_total 9312
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 57337
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175402
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 276
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 201
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 9110
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 8702
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 382
telemt_user_connections_total{user="hello"} 175405
telemt_user_connections_current{user="hello"} 442
telemt_user_octets_from_client{user="hello"} 1489690420 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 60143646612 (56.01 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 31590.2 (8h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 178244
telemt_connections_bad_total 254
telemt_handshake_timeouts_total 1704
telemt_upstream_connect_attempt_total 7056
telemt_upstream_connect_success_total 7028
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 7056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3915
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 5454
telemt_me_reconnect_success_total 5430
telemt_me_reader_eof_total 5792
telemt_me_idle_close_by_peer_total 5792
telemt_me_route_drop_no_conn_total 53550
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167406
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 672
telemt_desync_full_logged_total 219
telemt_desync_suppressed_total 453
telemt_desync_frames_bucket_total{bucket="1_2"} 208
telemt_desync_frames_bucket_total{bucket="3_10"} 262
telemt_desync_frames_bucket_total{bucket="gt_10"} 202
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 5482
telemt_me_writer_restored_same_endpoint_total 5422
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 167414
telemt_user_connections_current{user="hello"} 781
telemt_user_octets_from_client{user="hello"} 1638818884 (1.53 GB)
telemt_user_octets_to_client{user="hello"} 63041330780 (58.71 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 98
```