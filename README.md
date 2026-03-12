# Server Metrics 2026-03-12 12:27:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 23318.3 (6h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 794507
telemt_connections_bad_total 1592
telemt_handshake_timeouts_total 5627
telemt_upstream_connect_attempt_total 4645
telemt_upstream_connect_success_total 4616
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 4645
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2111
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 326
telemt_me_reconnect_attempts_total 7322
telemt_me_reconnect_success_total 3429
telemt_me_reader_eof_total 3671
telemt_me_idle_close_by_peer_total 3671
telemt_me_route_drop_no_conn_total 281774
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 764831
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4016
telemt_desync_full_logged_total 1009
telemt_desync_suppressed_total 3007
telemt_desync_frames_bucket_total{bucket="1_2"} 1010
telemt_desync_frames_bucket_total{bucket="3_10"} 1454
telemt_desync_frames_bucket_total{bucket="gt_10"} 1552
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3584
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3416
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 764674
telemt_user_connections_current{user="hello"} 1711
telemt_user_octets_from_client{user="hello"} 13147854208 (12.24 GB)
telemt_user_octets_to_client{user="hello"} 213385838404 (198.73 GB)
telemt_user_unique_ips_current{user="hello"} 447
telemt_user_unique_ips_recent_window{user="hello"} 248
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 52939.0 (14h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 403429
telemt_connections_bad_total 4933
telemt_handshake_timeouts_total 21311
telemt_upstream_connect_attempt_total 12866
telemt_upstream_connect_success_total 12859
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 12866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6509
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1054
telemt_me_reconnect_attempts_total 10100
telemt_me_reconnect_success_total 10043
telemt_me_reader_eof_total 10675
telemt_me_idle_close_by_peer_total 10675
telemt_me_route_drop_no_conn_total 115805
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 355447
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1154
telemt_desync_full_logged_total 377
telemt_desync_suppressed_total 777
telemt_desync_frames_bucket_total{bucket="1_2"} 452
telemt_desync_frames_bucket_total{bucket="3_10"} 396
telemt_desync_frames_bucket_total{bucket="gt_10"} 306
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 10135
telemt_me_writer_restored_same_endpoint_total 10034
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 355909
telemt_user_connections_current{user="hello"} 607
telemt_user_octets_from_client{user="hello"} 4784997947 (4.46 GB)
telemt_user_octets_to_client{user="hello"} 126945092414 (118.23 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 52938.9 (14h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 912846
telemt_connections_bad_total 5052
telemt_handshake_timeouts_total 68458
telemt_upstream_connect_attempt_total 12964
telemt_upstream_connect_success_total 12959
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 12964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7076
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5826
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 859
telemt_me_reconnect_attempts_total 10055
telemt_me_reconnect_success_total 9971
telemt_me_reader_eof_total 10492
telemt_me_idle_close_by_peer_total 10492
telemt_me_route_drop_no_conn_total 223451
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 623128
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2866
telemt_desync_full_logged_total 856
telemt_desync_suppressed_total 2010
telemt_desync_frames_bucket_total{bucket="1_2"} 411
telemt_desync_frames_bucket_total{bucket="3_10"} 1010
telemt_desync_frames_bucket_total{bucket="gt_10"} 1445
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 9994
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 9930
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 623362
telemt_user_connections_current{user="hello"} 1069
telemt_user_octets_from_client{user="hello"} 8202871832 (7.64 GB)
telemt_user_octets_to_client{user="hello"} 195895470081 (182.44 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 52939.3 (14h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 510345
telemt_connections_bad_total 7630
telemt_handshake_timeouts_total 47162
telemt_upstream_connect_attempt_total 14232
telemt_upstream_connect_success_total 14176
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 14232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 1266
telemt_me_reconnect_attempts_total 12769
telemt_me_reconnect_success_total 11539
telemt_me_reader_eof_total 12234
telemt_me_idle_close_by_peer_total 12234
telemt_me_route_drop_no_conn_total 167593
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 425349
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 852
telemt_desync_full_logged_total 298
telemt_desync_suppressed_total 554
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 358
telemt_desync_frames_bucket_total{bucket="gt_10"} 245
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11661
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11518
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 425172
telemt_user_connections_current{user="hello"} 696
telemt_user_octets_from_client{user="hello"} 4856967188 (4.52 GB)
telemt_user_octets_to_client{user="hello"} 164586279908 (153.28 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 52939.1 (14h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 573843
telemt_connections_bad_total 1696
telemt_handshake_timeouts_total 4533
telemt_upstream_connect_attempt_total 17160
telemt_upstream_connect_success_total 16956
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 17160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8214
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_timeout_total 965
telemt_me_reconnect_attempts_total 20255
telemt_me_reconnect_success_total 14312
telemt_me_reader_eof_total 14972
telemt_me_idle_close_by_peer_total 14972
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 191926
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 536191
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2254
telemt_desync_full_logged_total 758
telemt_desync_suppressed_total 1496
telemt_desync_frames_bucket_total{bucket="1_2"} 645
telemt_desync_frames_bucket_total{bucket="3_10"} 792
telemt_desync_frames_bucket_total{bucket="gt_10"} 817
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 14636
telemt_me_refill_failed_total 184
telemt_me_writer_restored_same_endpoint_total 14285
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 536105
telemt_user_connections_current{user="hello"} 780
telemt_user_octets_from_client{user="hello"} 6226629456 (5.80 GB)
telemt_user_octets_to_client{user="hello"} 136910616504 (127.51 GB)
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 161
```