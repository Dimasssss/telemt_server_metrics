# Server Metrics 2026-03-10 17:33:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 11178.7 (3h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 372795
telemt_connections_bad_total 2908
telemt_handshake_timeouts_total 1810
telemt_upstream_connect_attempt_total 2144
telemt_upstream_connect_success_total 2135
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 10776
telemt_me_reconnect_success_total 1511
telemt_me_reader_eof_total 1761
telemt_me_idle_close_by_peer_total 1761
telemt_me_route_drop_no_conn_total 161257
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 357103
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1669
telemt_desync_full_logged_total 467
telemt_desync_suppressed_total 1202
telemt_desync_frames_bucket_total{bucket="1_2"} 443
telemt_desync_frames_bucket_total{bucket="3_10"} 631
telemt_desync_frames_bucket_total{bucket="gt_10"} 595
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1799
telemt_me_refill_failed_total 289
telemt_me_writer_restored_same_endpoint_total 1505
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 288
telemt_user_connections_total{user="hello"} 357034
telemt_user_connections_current{user="hello"} 1380
telemt_user_octets_from_client{user="hello"} 4668871760 (4.35 GB)
telemt_user_octets_to_client{user="hello"} 104724220116 (97.53 GB)
telemt_user_unique_ips_current{user="hello"} 348
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 11235.3 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148064
telemt_connections_bad_total 1691
telemt_handshake_timeouts_total 9745
telemt_upstream_connect_attempt_total 2563
telemt_upstream_connect_success_total 2550
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1222
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 1957
telemt_me_reconnect_success_total 1946
telemt_me_reader_eof_total 2018
telemt_me_idle_close_by_peer_total 2018
telemt_me_route_drop_no_conn_total 42444
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128916
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 598
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 424
telemt_desync_frames_bucket_total{bucket="1_2"} 232
telemt_desync_frames_bucket_total{bucket="3_10"} 197
telemt_desync_frames_bucket_total{bucket="gt_10"} 169
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1957
telemt_me_writer_restored_same_endpoint_total 1925
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 128895
telemt_user_connections_current{user="hello"} 469
telemt_user_octets_from_client{user="hello"} 1658553964 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 34534448976 (32.16 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 11235.3 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 283847
telemt_connections_bad_total 795
telemt_handshake_timeouts_total 30854
telemt_upstream_connect_attempt_total 3854
telemt_upstream_connect_success_total 3788
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 3854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1394
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 3324
telemt_me_reconnect_success_total 2131
telemt_me_reader_eof_total 2231
telemt_me_idle_close_by_peer_total 2231
telemt_me_route_drop_no_conn_total 90810
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 229518
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 694
telemt_desync_full_logged_total 202
telemt_desync_suppressed_total 492
telemt_desync_frames_bucket_total{bucket="1_2"} 185
telemt_desync_frames_bucket_total{bucket="3_10"} 234
telemt_desync_frames_bucket_total{bucket="gt_10"} 275
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2199
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2120
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 230493
telemt_user_connections_current{user="hello"} 874
telemt_user_octets_from_client{user="hello"} 3186188629 (2.97 GB)
telemt_user_octets_to_client{user="hello"} 66720063421 (62.14 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 11235.6 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179822
telemt_connections_bad_total 11003
telemt_handshake_timeouts_total 18041
telemt_upstream_connect_attempt_total 2832
telemt_upstream_connect_success_total 2832
telemt_upstream_connect_attempts_per_request{bucket="1"} 2832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1307
telemt_me_keepalive_timeout_total 49
telemt_me_reconnect_attempts_total 2235
telemt_me_reconnect_success_total 2220
telemt_me_reader_eof_total 2303
telemt_me_idle_close_by_peer_total 2303
telemt_me_route_drop_no_conn_total 57711
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143032
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 452
telemt_desync_full_logged_total 180
telemt_desync_suppressed_total 272
telemt_desync_frames_bucket_total{bucket="1_2"} 148
telemt_desync_frames_bucket_total{bucket="3_10"} 163
telemt_desync_frames_bucket_total{bucket="gt_10"} 141
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2239
telemt_me_writer_restored_same_endpoint_total 2209
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 142871
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 2349129644 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 40191731788 (37.43 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 11235.3 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192312
telemt_connections_bad_total 795
telemt_handshake_timeouts_total 1580
telemt_upstream_connect_attempt_total 3444
telemt_upstream_connect_success_total 3434
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1634
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 75
telemt_me_reconnect_attempts_total 2828
telemt_me_reconnect_success_total 2810
telemt_me_reader_eof_total 2888
telemt_me_idle_close_by_peer_total 2888
telemt_me_route_drop_no_conn_total 70739
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180370
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 959
telemt_desync_full_logged_total 335
telemt_desync_suppressed_total 624
telemt_desync_frames_bucket_total{bucket="1_2"} 389
telemt_desync_frames_bucket_total{bucket="3_10"} 414
telemt_desync_frames_bucket_total{bucket="gt_10"} 156
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2835
telemt_me_writer_restored_same_endpoint_total 2810
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 180307
telemt_user_connections_current{user="hello"} 604
telemt_user_octets_from_client{user="hello"} 4149684944 (3.86 GB)
telemt_user_octets_to_client{user="hello"} 53788597032 (50.09 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 140
```