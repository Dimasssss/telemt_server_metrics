# Server Metrics 2026-03-04 15:07:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 64626.7 (17h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1202093
telemt_connections_bad_total 14021
telemt_handshake_timeouts_total 21931
telemt_upstream_connect_attempt_total 37769
telemt_upstream_connect_success_total 37602
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 37602
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16842
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 432
telemt_me_reconnect_attempts_total 8182
telemt_me_reconnect_success_total 8120
telemt_me_reader_eof_total 8385
telemt_me_idle_close_by_peer_total 8384
telemt_me_route_drop_no_conn_total 443551
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 252
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2330
telemt_desync_full_logged_total 759
telemt_desync_suppressed_total 1571
telemt_desync_frames_bucket_total{bucket="1_2"} 697
telemt_desync_frames_bucket_total{bucket="3_10"} 874
telemt_desync_frames_bucket_total{bucket="gt_10"} 759
telemt_pool_swap_total 17
telemt_pool_force_close_total 715
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8385
telemt_me_writer_restored_same_endpoint_total 8098
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 967139
telemt_user_connections_current{user="hello"} 1018
telemt_user_octets_from_client{user="hello"} 12986706688 (12.09 GB)
telemt_user_octets_to_client{user="hello"} 325989735648 (303.60 GB)
telemt_user_unique_ips_current{user="hello"} 106
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 64623.1 (17h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 456924
telemt_connections_bad_total 3761
telemt_handshake_timeouts_total 30258
telemt_upstream_connect_attempt_total 116903
telemt_upstream_connect_success_total 115203
telemt_upstream_connect_fail_total 812
telemt_upstream_connect_attempts_per_request{bucket="1"} 115197
telemt_upstream_connect_attempts_per_request{bucket="2"} 818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40215
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 812
telemt_me_keepalive_timeout_total 1539
telemt_me_reconnect_attempts_total 63858
telemt_me_reconnect_success_total 63757
telemt_me_reader_eof_total 65415
telemt_me_idle_close_by_peer_total 65414
telemt_me_route_drop_no_conn_total 186538
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 270
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1055
telemt_desync_full_logged_total 321
telemt_desync_suppressed_total 734
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 433
telemt_desync_frames_bucket_total{bucket="gt_10"} 423
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 65495
telemt_me_writer_restored_same_endpoint_total 63732
telemt_me_writer_removed_unexpected_minus_restored_total 1763
telemt_user_connections_total{user="hello"} 359932
telemt_user_connections_current{user="hello"} 445
telemt_user_octets_from_client{user="hello"} 5701441204 (5.31 GB)
telemt_user_octets_to_client{user="hello"} 114541072024 (106.67 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 64621.9 (17h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 921074
telemt_connections_bad_total 191659
telemt_handshake_timeouts_total 29807
telemt_upstream_connect_attempt_total 85745
telemt_upstream_connect_success_total 85177
telemt_upstream_connect_fail_total 274
telemt_upstream_connect_attempts_per_request{bucket="1"} 85176
telemt_upstream_connect_attempts_per_request{bucket="2"} 275
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50400
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34549
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 274
telemt_me_keepalive_timeout_total 1110
telemt_me_reconnect_attempts_total 38445
telemt_me_reconnect_success_total 38344
telemt_me_reader_eof_total 40350
telemt_me_idle_close_by_peer_total 40346
telemt_me_route_drop_no_conn_total 334987
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_single_endpoint_shadow_rotate_total 266
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1954
telemt_desync_full_logged_total 646
telemt_desync_suppressed_total 1308
telemt_desync_frames_bucket_total{bucket="1_2"} 601
telemt_desync_frames_bucket_total{bucket="3_10"} 630
telemt_desync_frames_bucket_total{bucket="gt_10"} 723
telemt_pool_swap_total 7
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 40362
telemt_me_writer_restored_same_endpoint_total 38322
telemt_me_writer_removed_unexpected_minus_restored_total 2040
telemt_user_connections_total{user="hello"} 654860
telemt_user_connections_current{user="hello"} 702
telemt_user_octets_from_client{user="hello"} 13427285004 (12.51 GB)
telemt_user_octets_to_client{user="hello"} 221868354472 (206.63 GB)
telemt_user_unique_ips_current{user="hello"} 58
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 11299.2 (3h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168894
telemt_connections_bad_total 16278
telemt_handshake_timeouts_total 5272
telemt_upstream_connect_attempt_total 5074
telemt_upstream_connect_success_total 5074
telemt_upstream_connect_attempts_per_request{bucket="1"} 5074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3033
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2041
telemt_me_keepalive_timeout_total 57
telemt_me_reconnect_attempts_total 858
telemt_me_reconnect_success_total 869
telemt_me_reader_eof_total 877
telemt_me_idle_close_by_peer_total 877
telemt_me_route_drop_no_conn_total 55208
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 48
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 193
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 84
telemt_pool_swap_total 3
telemt_pool_force_close_total 110
telemt_me_writer_removed_unexpected_total 877
telemt_me_writer_restored_same_endpoint_total 848
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 141855
telemt_user_connections_current{user="hello"} 451
telemt_user_octets_from_client{user="hello"} 1864128996 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 64486775652 (60.06 GB)
telemt_user_unique_ips_current{user="hello"} 39
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 11658.5 (3h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198968
telemt_connections_bad_total 1859
telemt_handshake_timeouts_total 3241
telemt_upstream_connect_attempt_total 6339
telemt_upstream_connect_success_total 6308
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 6308
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2624
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 1275
telemt_me_reconnect_success_total 1283
telemt_me_reader_eof_total 1309
telemt_me_idle_close_by_peer_total 1309
telemt_me_route_drop_no_conn_total 75352
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 48
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 478
telemt_desync_full_logged_total 181
telemt_desync_suppressed_total 297
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 203
telemt_desync_frames_bucket_total{bucket="gt_10"} 208
telemt_pool_swap_total 2
telemt_pool_force_close_total 101
telemt_me_writer_removed_unexpected_total 1309
telemt_me_writer_restored_same_endpoint_total 1263
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 172786
telemt_user_connections_current{user="hello"} 620
telemt_user_octets_from_client{user="hello"} 2793362704 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 47880759964 (44.59 GB)
telemt_user_unique_ips_current{user="hello"} 50
```