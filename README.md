# Server Metrics 2026-03-11 08:18:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 64289.5 (17h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1320426
telemt_connections_bad_total 15008
telemt_handshake_timeouts_total 39843
telemt_upstream_connect_attempt_total 13331
telemt_upstream_connect_success_total 13322
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 13331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6715
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6544
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 749
telemt_me_reconnect_attempts_total 21750
telemt_me_reconnect_success_total 10065
telemt_me_reader_eof_total 10930
telemt_me_idle_close_by_peer_total 10930
telemt_me_route_drop_no_conn_total 486523
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1195909
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5921
telemt_desync_full_logged_total 1642
telemt_desync_suppressed_total 4279
telemt_desync_frames_bucket_total{bucket="1_2"} 1545
telemt_desync_frames_bucket_total{bucket="3_10"} 2259
telemt_desync_frames_bucket_total{bucket="gt_10"} 2117
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10529
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 10059
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 1195558
telemt_user_connections_current{user="hello"} 1277
telemt_user_octets_from_client{user="hello"} 15913805568 (14.82 GB)
telemt_user_octets_to_client{user="hello"} 348426762728 (324.50 GB)
telemt_user_unique_ips_current{user="hello"} 345
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 64346.4 (17h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 513087
telemt_connections_bad_total 7559
telemt_handshake_timeouts_total 28829
telemt_upstream_connect_attempt_total 22317
telemt_upstream_connect_success_total 19396
telemt_upstream_connect_fail_total 2921
telemt_upstream_connect_attempts_per_request{bucket="1"} 22317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8775
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8378
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2921
telemt_me_keepalive_timeout_total 2057
telemt_me_reconnect_attempts_total 14052
telemt_me_reconnect_success_total 13222
telemt_me_reader_eof_total 13987
telemt_me_idle_close_by_peer_total 13985
telemt_me_route_drop_no_conn_total 218616
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 434378
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2124
telemt_desync_full_logged_total 650
telemt_desync_suppressed_total 1474
telemt_desync_frames_bucket_total{bucket="1_2"} 697
telemt_desync_frames_bucket_total{bucket="3_10"} 769
telemt_desync_frames_bucket_total{bucket="gt_10"} 658
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 13377
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 13200
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 436620
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 4253967794 (3.96 GB)
telemt_user_octets_to_client{user="hello"} 117002320228 (108.97 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 64346.2 (17h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 864570
telemt_connections_bad_total 7168
telemt_handshake_timeouts_total 53804
telemt_upstream_connect_attempt_total 17494
telemt_upstream_connect_success_total 17280
telemt_upstream_connect_fail_total 214
telemt_upstream_connect_attempts_per_request{bucket="1"} 17494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7783
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 214
telemt_me_keepalive_timeout_total 751
telemt_me_reconnect_attempts_total 25336
telemt_me_reconnect_success_total 12977
telemt_me_reader_eof_total 13963
telemt_me_idle_close_by_peer_total 13963
telemt_me_route_drop_no_conn_total 292046
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 767351
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2230
telemt_desync_full_logged_total 659
telemt_desync_suppressed_total 1571
telemt_desync_frames_bucket_total{bucket="1_2"} 528
telemt_desync_frames_bucket_total{bucket="3_10"} 810
telemt_desync_frames_bucket_total{bucket="gt_10"} 892
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 13526
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 12966
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 549
telemt_user_connections_total{user="hello"} 768128
telemt_user_connections_current{user="hello"} 671
telemt_user_octets_from_client{user="hello"} 9133754317 (8.51 GB)
telemt_user_octets_to_client{user="hello"} 232860595885 (216.87 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 64346.6 (17h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 654507
telemt_connections_bad_total 60204
telemt_handshake_timeouts_total 63960
telemt_upstream_connect_attempt_total 17915
telemt_upstream_connect_success_total 17915
telemt_upstream_connect_attempts_per_request{bucket="1"} 17915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7914
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 683
telemt_me_reconnect_attempts_total 15745
telemt_me_reconnect_success_total 14693
telemt_me_reader_eof_total 15610
telemt_me_idle_close_by_peer_total 15609
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 203240
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 509310
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1222
telemt_desync_full_logged_total 460
telemt_desync_suppressed_total 762
telemt_desync_frames_bucket_total{bucket="1_2"} 405
telemt_desync_frames_bucket_total{bucket="3_10"} 465
telemt_desync_frames_bucket_total{bucket="gt_10"} 352
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 14865
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 14671
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 508686
telemt_user_connections_current{user="hello"} 455
telemt_user_octets_from_client{user="hello"} 6008557896 (5.60 GB)
telemt_user_octets_to_client{user="hello"} 140488933904 (130.84 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 64346.3 (17h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 687116
telemt_connections_bad_total 5976
telemt_handshake_timeouts_total 6476
telemt_upstream_connect_attempt_total 17800
telemt_upstream_connect_success_total 17728
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 17800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8466
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 720
telemt_me_reconnect_attempts_total 18179
telemt_me_reconnect_success_total 14389
telemt_me_reader_eof_total 15211
telemt_me_idle_close_by_peer_total 15211
telemt_me_route_drop_no_conn_total 231733
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 626060
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2812
telemt_desync_full_logged_total 1060
telemt_desync_suppressed_total 1752
telemt_desync_frames_bucket_total{bucket="1_2"} 984
telemt_desync_frames_bucket_total{bucket="3_10"} 1177
telemt_desync_frames_bucket_total{bucket="gt_10"} 651
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 14689
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 14389
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 300
telemt_user_connections_total{user="hello"} 625754
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 10266299319 (9.56 GB)
telemt_user_octets_to_client{user="hello"} 228092867518 (212.43 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 85
```