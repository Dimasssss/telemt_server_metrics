# Server Metrics 2026-03-11 06:52:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 59099.6 (16h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1172924
telemt_connections_bad_total 13237
telemt_handshake_timeouts_total 38749
telemt_upstream_connect_attempt_total 12431
telemt_upstream_connect_success_total 12422
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 12431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6110
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 705
telemt_me_reconnect_attempts_total 21111
telemt_me_reconnect_success_total 9428
telemt_me_reader_eof_total 10248
telemt_me_idle_close_by_peer_total 10248
telemt_me_route_drop_no_conn_total 431131
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1056175
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5084
telemt_desync_full_logged_total 1419
telemt_desync_suppressed_total 3665
telemt_desync_frames_bucket_total{bucket="1_2"} 1366
telemt_desync_frames_bucket_total{bucket="3_10"} 1902
telemt_desync_frames_bucket_total{bucket="gt_10"} 1816
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 9885
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9422
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 457
telemt_user_connections_total{user="hello"} 1055836
telemt_user_connections_current{user="hello"} 1252
telemt_user_octets_from_client{user="hello"} 14029783372 (13.07 GB)
telemt_user_octets_to_client{user="hello"} 309777402904 (288.50 GB)
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 59156.3 (16h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 452740
telemt_connections_bad_total 5538
telemt_handshake_timeouts_total 22031
telemt_upstream_connect_attempt_total 21165
telemt_upstream_connect_success_total 18252
telemt_upstream_connect_fail_total 2913
telemt_upstream_connect_attempts_per_request{bucket="1"} 21165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7807
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2913
telemt_me_keepalive_timeout_total 2030
telemt_me_reconnect_attempts_total 13169
telemt_me_reconnect_success_total 12344
telemt_me_reader_eof_total 13050
telemt_me_idle_close_by_peer_total 13048
telemt_me_route_drop_no_conn_total 203518
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 387183
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1971
telemt_desync_full_logged_total 600
telemt_desync_suppressed_total 1371
telemt_desync_frames_bucket_total{bucket="1_2"} 633
telemt_desync_frames_bucket_total{bucket="3_10"} 709
telemt_desync_frames_bucket_total{bucket="gt_10"} 629
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 12488
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 12322
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 389452
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 3866899598 (3.60 GB)
telemt_user_octets_to_client{user="hello"} 98883543536 (92.09 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 59156.3 (16h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 769745
telemt_connections_bad_total 6720
telemt_handshake_timeouts_total 41711
telemt_upstream_connect_attempt_total 15860
telemt_upstream_connect_success_total 15657
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 15860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7040
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_timeout_total 706
telemt_me_reconnect_attempts_total 22699
telemt_me_reconnect_success_total 11626
telemt_me_reader_eof_total 12523
telemt_me_idle_close_by_peer_total 12523
telemt_me_route_drop_no_conn_total 259823
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 688366
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1961
telemt_desync_full_logged_total 567
telemt_desync_suppressed_total 1394
telemt_desync_frames_bucket_total{bucket="1_2"} 463
telemt_desync_frames_bucket_total{bucket="3_10"} 705
telemt_desync_frames_bucket_total{bucket="gt_10"} 793
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 12121
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 11615
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 495
telemt_user_connections_total{user="hello"} 689196
telemt_user_connections_current{user="hello"} 582
telemt_user_octets_from_client{user="hello"} 8112021969 (7.55 GB)
telemt_user_octets_to_client{user="hello"} 203472353589 (189.50 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 59156.7 (16h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 586944
telemt_connections_bad_total 55455
telemt_handshake_timeouts_total 59389
telemt_upstream_connect_attempt_total 16783
telemt_upstream_connect_success_total 16783
telemt_upstream_connect_attempts_per_request{bucket="1"} 16783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7371
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 651
telemt_me_reconnect_attempts_total 14873
telemt_me_reconnect_success_total 13825
telemt_me_reader_eof_total 14677
telemt_me_idle_close_by_peer_total 14677
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 177266
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 453855
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 962
telemt_desync_full_logged_total 397
telemt_desync_suppressed_total 565
telemt_desync_frames_bucket_total{bucket="1_2"} 346
telemt_desync_frames_bucket_total{bucket="3_10"} 357
telemt_desync_frames_bucket_total{bucket="gt_10"} 259
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13986
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 13803
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 453373
telemt_user_connections_current{user="hello"} 495
telemt_user_octets_from_client{user="hello"} 5435812820 (5.06 GB)
telemt_user_octets_to_client{user="hello"} 124315825036 (115.78 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 59156.1 (16h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 611379
telemt_connections_bad_total 5966
telemt_handshake_timeouts_total 4342
telemt_upstream_connect_attempt_total 16696
telemt_upstream_connect_success_total 16627
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 16696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7956
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 679
telemt_me_reconnect_attempts_total 17339
telemt_me_reconnect_success_total 13553
telemt_me_reader_eof_total 14321
telemt_me_idle_close_by_peer_total 14321
telemt_me_route_drop_no_conn_total 201864
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 556895
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2618
telemt_desync_full_logged_total 999
telemt_desync_suppressed_total 1619
telemt_desync_frames_bucket_total{bucket="1_2"} 933
telemt_desync_frames_bucket_total{bucket="3_10"} 1121
telemt_desync_frames_bucket_total{bucket="gt_10"} 564
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 13846
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 13553
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 293
telemt_user_connections_total{user="hello"} 556625
telemt_user_connections_current{user="hello"} 645
telemt_user_octets_from_client{user="hello"} 9651505407 (8.99 GB)
telemt_user_octets_to_client{user="hello"} 203594015646 (189.61 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 92
```