# Server Metrics 2026-03-15 09:49:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 41696.6 (11h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 953945
telemt_connections_bad_total 51998
telemt_handshake_timeouts_total 7217
telemt_upstream_connect_attempt_total 8373
telemt_upstream_connect_success_total 8336
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 8373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3938
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6278
telemt_me_reconnect_success_total 6242
telemt_me_reader_eof_total 6610
telemt_me_idle_close_by_peer_total 6610
telemt_me_route_drop_no_conn_total 314456
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 804807
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2857
telemt_desync_full_logged_total 837
telemt_desync_suppressed_total 2020
telemt_desync_frames_bucket_total{bucket="1_2"} 672
telemt_desync_frames_bucket_total{bucket="3_10"} 1108
telemt_desync_frames_bucket_total{bucket="gt_10"} 1077
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6331
telemt_me_writer_restored_same_endpoint_total 6231
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 804818
telemt_user_connections_current{user="hello"} 1999
telemt_user_octets_from_client{user="hello"} 11654241056 (10.85 GB)
telemt_user_octets_to_client{user="hello"} 309783326120 (288.51 GB)
telemt_user_unique_ips_current{user="hello"} 562
telemt_user_unique_ips_recent_window{user="hello"} 267
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 41697.3 (11h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 376598
telemt_connections_bad_total 21092
telemt_handshake_timeouts_total 14801
telemt_upstream_connect_attempt_total 11085
telemt_upstream_connect_success_total 11027
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 11085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4953
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 8659
telemt_me_reconnect_success_total 8603
telemt_me_reader_eof_total 9110
telemt_me_idle_close_by_peer_total 9110
telemt_me_route_drop_no_conn_total 95376
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 297769
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1056
telemt_desync_full_logged_total 365
telemt_desync_suppressed_total 691
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 392
telemt_desync_frames_bucket_total{bucket="gt_10"} 320
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 8683
telemt_me_writer_restored_same_endpoint_total 8595
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 298057
telemt_user_connections_current{user="hello"} 736
telemt_user_octets_from_client{user="hello"} 4359889787 (4.06 GB)
telemt_user_octets_to_client{user="hello"} 111976617388 (104.29 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 41697.4 (11h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 685045
telemt_connections_bad_total 22897
telemt_handshake_timeouts_total 70001
telemt_upstream_connect_attempt_total 9309
telemt_upstream_connect_success_total 9269
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 9309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4375
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_reconnect_attempts_total 7206
telemt_me_reconnect_success_total 7160
telemt_me_reader_eof_total 7581
telemt_me_idle_close_by_peer_total 7581
telemt_me_route_drop_no_conn_total 197561
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 521384
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1111
telemt_desync_full_logged_total 413
telemt_desync_suppressed_total 698
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 394
telemt_desync_frames_bucket_total{bucket="gt_10"} 474
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 7249
telemt_me_writer_restored_same_endpoint_total 7141
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 520812
telemt_user_connections_current{user="hello"} 1077
telemt_user_octets_from_client{user="hello"} 7812229668 (7.28 GB)
telemt_user_octets_to_client{user="hello"} 207906963440 (193.63 GB)
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 41697.4 (11h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 396322
telemt_connections_bad_total 53428
telemt_handshake_timeouts_total 24403
telemt_upstream_connect_attempt_total 12900
telemt_upstream_connect_success_total 12585
telemt_upstream_connect_fail_total 315
telemt_upstream_connect_attempts_per_request{bucket="1"} 12900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5911
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6671
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 315
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 29466
telemt_me_reconnect_success_total 10482
telemt_me_reader_eof_total 11390
telemt_me_idle_close_by_peer_total 11390
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 109132
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 296807
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 726
telemt_desync_full_logged_total 178
telemt_desync_suppressed_total 548
telemt_desync_frames_bucket_total{bucket="1_2"} 174
telemt_desync_frames_bucket_total{bucket="3_10"} 298
telemt_desync_frames_bucket_total{bucket="gt_10"} 254
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 11169
telemt_me_refill_failed_total 593
telemt_me_writer_restored_same_endpoint_total 10452
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 687
telemt_user_connections_total{user="hello"} 296716
telemt_user_connections_current{user="hello"} 613
telemt_user_octets_from_client{user="hello"} 3528307096 (3.29 GB)
telemt_user_octets_to_client{user="hello"} 95779745856 (89.20 GB)
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 41698.1 (11h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 382678
telemt_connections_bad_total 4162
telemt_handshake_timeouts_total 4643
telemt_upstream_connect_attempt_total 9335
telemt_upstream_connect_success_total 9292
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 9335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5057
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_reconnect_attempts_total 7230
telemt_me_reconnect_success_total 7194
telemt_me_reader_eof_total 7649
telemt_me_idle_close_by_peer_total 7649
telemt_me_route_drop_no_conn_total 101669
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 318260
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1221
telemt_desync_full_logged_total 394
telemt_desync_suppressed_total 827
telemt_desync_frames_bucket_total{bucket="1_2"} 364
telemt_desync_frames_bucket_total{bucket="3_10"} 498
telemt_desync_frames_bucket_total{bucket="gt_10"} 359
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7271
telemt_me_writer_restored_same_endpoint_total 7186
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 318268
telemt_user_connections_current{user="hello"} 899
telemt_user_octets_from_client{user="hello"} 3918329180 (3.65 GB)
telemt_user_octets_to_client{user="hello"} 116685154932 (108.67 GB)
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 119
```