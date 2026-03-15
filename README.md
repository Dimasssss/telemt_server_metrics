# Server Metrics 2026-03-15 10:15:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 43232.2 (12h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1030056
telemt_connections_bad_total 61043
telemt_handshake_timeouts_total 8011
telemt_upstream_connect_attempt_total 8627
telemt_upstream_connect_success_total 8589
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 8627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4046
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6486
telemt_me_reconnect_success_total 6447
telemt_me_reader_eof_total 6817
telemt_me_idle_close_by_peer_total 6817
telemt_me_route_drop_no_conn_total 338945
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 867528
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3146
telemt_desync_full_logged_total 899
telemt_desync_suppressed_total 2247
telemt_desync_frames_bucket_total{bucket="1_2"} 756
telemt_desync_frames_bucket_total{bucket="3_10"} 1233
telemt_desync_frames_bucket_total{bucket="gt_10"} 1157
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6538
telemt_me_writer_restored_same_endpoint_total 6436
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 867528
telemt_user_connections_current{user="hello"} 2076
telemt_user_octets_from_client{user="hello"} 12526864980 (11.67 GB)
telemt_user_octets_to_client{user="hello"} 333236566200 (310.35 GB)
telemt_user_unique_ips_current{user="hello"} 553
telemt_user_unique_ips_recent_window{user="hello"} 281
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 43233.0 (12h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 405055
telemt_connections_bad_total 22362
telemt_handshake_timeouts_total 16954
telemt_upstream_connect_attempt_total 11401
telemt_upstream_connect_success_total 11341
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 11401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5102
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 8925
telemt_me_reconnect_success_total 8868
telemt_me_reader_eof_total 9395
telemt_me_idle_close_by_peer_total 9395
telemt_me_route_drop_no_conn_total 103323
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 320435
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1146
telemt_desync_full_logged_total 393
telemt_desync_suppressed_total 753
telemt_desync_frames_bucket_total{bucket="1_2"} 381
telemt_desync_frames_bucket_total{bucket="3_10"} 423
telemt_desync_frames_bucket_total{bucket="gt_10"} 342
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 8953
telemt_me_writer_restored_same_endpoint_total 8860
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 320719
telemt_user_connections_current{user="hello"} 659
telemt_user_octets_from_client{user="hello"} 4694615931 (4.37 GB)
telemt_user_octets_to_client{user="hello"} 121089150880 (112.77 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 43233.0 (12h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 751661
telemt_connections_bad_total 25303
telemt_handshake_timeouts_total 75301
telemt_upstream_connect_attempt_total 9528
telemt_upstream_connect_success_total 9488
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 9528
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4490
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_reconnect_attempts_total 7373
telemt_me_reconnect_success_total 7326
telemt_me_reader_eof_total 7756
telemt_me_idle_close_by_peer_total 7756
telemt_me_route_drop_no_conn_total 214389
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 562354
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1240
telemt_desync_full_logged_total 458
telemt_desync_suppressed_total 782
telemt_desync_frames_bucket_total{bucket="1_2"} 270
telemt_desync_frames_bucket_total{bucket="3_10"} 449
telemt_desync_frames_bucket_total{bucket="gt_10"} 521
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 7420
telemt_me_writer_restored_same_endpoint_total 7307
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 561780
telemt_user_connections_current{user="hello"} 1165
telemt_user_octets_from_client{user="hello"} 8287454100 (7.72 GB)
telemt_user_octets_to_client{user="hello"} 225049127244 (209.59 GB)
telemt_user_unique_ips_current{user="hello"} 346
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 43233.0 (12h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 424026
telemt_connections_bad_total 55111
telemt_handshake_timeouts_total 25163
telemt_upstream_connect_attempt_total 13094
telemt_upstream_connect_success_total 12772
telemt_upstream_connect_fail_total 322
telemt_upstream_connect_attempts_per_request{bucket="1"} 13094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6046
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6723
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 322
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 30978
telemt_me_reconnect_success_total 10619
telemt_me_reader_eof_total 11569
telemt_me_idle_close_by_peer_total 11569
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 118089
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 318128
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 740
telemt_desync_full_logged_total 183
telemt_desync_suppressed_total 557
telemt_desync_frames_bucket_total{bucket="1_2"} 178
telemt_desync_frames_bucket_total{bucket="3_10"} 303
telemt_desync_frames_bucket_total{bucket="gt_10"} 259
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 11348
telemt_me_refill_failed_total 636
telemt_me_writer_restored_same_endpoint_total 10589
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 729
telemt_user_connections_total{user="hello"} 318039
telemt_user_connections_current{user="hello"} 544
telemt_user_octets_from_client{user="hello"} 3852867572 (3.59 GB)
telemt_user_octets_to_client{user="hello"} 102742897320 (95.69 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 43233.9 (12h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 419490
telemt_connections_bad_total 5753
telemt_handshake_timeouts_total 6125
telemt_upstream_connect_attempt_total 9597
telemt_upstream_connect_success_total 9552
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 9597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_reconnect_attempts_total 7439
telemt_me_reconnect_success_total 7402
telemt_me_reader_eof_total 7876
telemt_me_idle_close_by_peer_total 7876
telemt_me_route_drop_no_conn_total 109641
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 347395
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1325
telemt_desync_full_logged_total 426
telemt_desync_suppressed_total 899
telemt_desync_frames_bucket_total{bucket="1_2"} 396
telemt_desync_frames_bucket_total{bucket="3_10"} 533
telemt_desync_frames_bucket_total{bucket="gt_10"} 396
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 7485
telemt_me_writer_restored_same_endpoint_total 7394
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 347399
telemt_user_connections_current{user="hello"} 844
telemt_user_octets_from_client{user="hello"} 4201155608 (3.91 GB)
telemt_user_octets_to_client{user="hello"} 128688443472 (119.85 GB)
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 114
```