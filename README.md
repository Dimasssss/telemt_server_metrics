# Server Metrics 2026-03-13 04:47:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 82106.5 (22h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2220454
telemt_connections_bad_total 31254
telemt_handshake_timeouts_total 23362
telemt_upstream_connect_attempt_total 16218
telemt_upstream_connect_success_total 16128
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 16218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_timeout_total 1304
telemt_me_reconnect_attempts_total 20889
telemt_me_reconnect_success_total 12024
telemt_me_reader_eof_total 12980
telemt_me_idle_close_by_peer_total 12979
telemt_me_route_drop_no_conn_total 846869
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2041993
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8955
telemt_desync_full_logged_total 2327
telemt_desync_suppressed_total 6628
telemt_desync_frames_bucket_total{bucket="1_2"} 2354
telemt_desync_frames_bucket_total{bucket="3_10"} 3234
telemt_desync_frames_bucket_total{bucket="gt_10"} 3367
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 12469
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 12011
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 445
telemt_user_connections_total{user="hello"} 2041417
telemt_user_connections_current{user="hello"} 970
telemt_user_octets_from_client{user="hello"} 29672713028 (27.63 GB)
telemt_user_octets_to_client{user="hello"} 704889385756 (656.48 GB)
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 111727.1 (31h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 901603
telemt_connections_bad_total 11924
telemt_handshake_timeouts_total 39733
telemt_upstream_connect_attempt_total 28333
telemt_upstream_connect_success_total 28302
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 28333
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3528
telemt_me_reconnect_attempts_total 21196
telemt_me_reconnect_success_total 21080
telemt_me_reader_eof_total 22467
telemt_me_idle_close_by_peer_total 22467
telemt_me_route_drop_no_conn_total 287482
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 813143
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3234
telemt_desync_full_logged_total 1017
telemt_desync_suppressed_total 2217
telemt_desync_frames_bucket_total{bucket="1_2"} 1293
telemt_desync_frames_bucket_total{bucket="3_10"} 1054
telemt_desync_frames_bucket_total{bucket="gt_10"} 887
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 21289
telemt_me_writer_restored_same_endpoint_total 21071
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 815042
telemt_user_connections_current{user="hello"} 298
telemt_user_octets_from_client{user="hello"} 13012274492 (12.12 GB)
telemt_user_octets_to_client{user="hello"} 313848987159 (292.29 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 111726.9 (31h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1862277
telemt_connections_bad_total 16984
telemt_handshake_timeouts_total 122523
telemt_upstream_connect_attempt_total 26021
telemt_upstream_connect_success_total 26011
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 26021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12257
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1641
telemt_me_reconnect_attempts_total 21349
telemt_me_reconnect_success_total 20080
telemt_me_reader_eof_total 21268
telemt_me_idle_close_by_peer_total 21267
telemt_me_route_drop_no_conn_total 601084
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1470389
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5121
telemt_desync_full_logged_total 1565
telemt_desync_suppressed_total 3556
telemt_desync_frames_bucket_total{bucket="1_2"} 819
telemt_desync_frames_bucket_total{bucket="3_10"} 1847
telemt_desync_frames_bucket_total{bucket="gt_10"} 2455
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 20272
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 20039
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 192
telemt_user_connections_total{user="hello"} 1469971
telemt_user_connections_current{user="hello"} 433
telemt_user_octets_from_client{user="hello"} 25406624092 (23.66 GB)
telemt_user_octets_to_client{user="hello"} 521556033609 (485.74 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 111727.3 (31h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1151610
telemt_connections_bad_total 13196
telemt_handshake_timeouts_total 74929
telemt_upstream_connect_attempt_total 38428
telemt_upstream_connect_success_total 36144
telemt_upstream_connect_fail_total 2147
telemt_upstream_connect_attempts_per_request{bucket="1"} 38154
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13772
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2146
telemt_me_keepalive_timeout_total 11390
telemt_me_reconnect_attempts_total 33632
telemt_me_reconnect_success_total 24699
telemt_me_reader_eof_total 26653
telemt_me_idle_close_by_peer_total 26646
telemt_me_route_drop_no_conn_total 409694
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 991043
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1952
telemt_desync_full_logged_total 644
telemt_desync_suppressed_total 1308
telemt_desync_frames_bucket_total{bucket="1_2"} 539
telemt_desync_frames_bucket_total{bucket="3_10"} 761
telemt_desync_frames_bucket_total{bucket="gt_10"} 652
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 25145
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 24675
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 446
telemt_user_connections_total{user="hello"} 996221
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 15250504645 (14.20 GB)
telemt_user_octets_to_client{user="hello"} 392985903714 (366.00 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 111727.1 (31h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1281192
telemt_connections_bad_total 12908
telemt_handshake_timeouts_total 10276
telemt_upstream_connect_attempt_total 35182
telemt_upstream_connect_success_total 34756
telemt_upstream_connect_fail_total 426
telemt_upstream_connect_attempts_per_request{bucket="1"} 35182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16832
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 426
telemt_me_keepalive_timeout_total 1939
telemt_me_reconnect_attempts_total 42913
telemt_me_reconnect_success_total 29180
telemt_me_reader_eof_total 30680
telemt_me_idle_close_by_peer_total 30680
telemt_me_seq_mismatch_total 39
telemt_me_route_drop_no_conn_total 474692
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1185592
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 43
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4324
telemt_desync_full_logged_total 1557
telemt_desync_suppressed_total 2767
telemt_desync_frames_bucket_total{bucket="1_2"} 1307
telemt_desync_frames_bucket_total{bucket="3_10"} 1412
telemt_desync_frames_bucket_total{bucket="gt_10"} 1605
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 29943
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 29129
telemt_me_writer_restored_fallback_total 51
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 763
telemt_user_connections_total{user="hello"} 1185446
telemt_user_connections_current{user="hello"} 532
telemt_user_octets_from_client{user="hello"} 14433833440 (13.44 GB)
telemt_user_octets_to_client{user="hello"} 403890156872 (376.15 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 63
```