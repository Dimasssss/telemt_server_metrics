# Server Metrics 2026-03-04 15:02:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 64319.8 (17h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1194396
telemt_connections_bad_total 14021
telemt_handshake_timeouts_total 21870
telemt_upstream_connect_attempt_total 37682
telemt_upstream_connect_success_total 37515
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 37515
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16800
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 431
telemt_me_reconnect_attempts_total 8182
telemt_me_reconnect_success_total 8120
telemt_me_reader_eof_total 8385
telemt_me_idle_close_by_peer_total 8384
telemt_me_route_drop_no_conn_total 440483
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 252
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2306
telemt_desync_full_logged_total 751
telemt_desync_suppressed_total 1555
telemt_desync_frames_bucket_total{bucket="1_2"} 682
telemt_desync_frames_bucket_total{bucket="3_10"} 874
telemt_desync_frames_bucket_total{bucket="gt_10"} 750
telemt_pool_swap_total 17
telemt_pool_force_close_total 715
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8385
telemt_me_writer_restored_same_endpoint_total 8098
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 959968
telemt_user_connections_current{user="hello"} 1007
telemt_user_octets_from_client{user="hello"} 12866766764 (11.98 GB)
telemt_user_octets_to_client{user="hello"} 323846803848 (301.61 GB)
telemt_user_unique_ips_current{user="hello"} 89
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 64315.9 (17h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 453957
telemt_connections_bad_total 3761
telemt_handshake_timeouts_total 30238
telemt_upstream_connect_attempt_total 116237
telemt_upstream_connect_success_total 114537
telemt_upstream_connect_fail_total 812
telemt_upstream_connect_attempts_per_request{bucket="1"} 114531
telemt_upstream_connect_attempts_per_request{bucket="2"} 818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39964
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 812
telemt_me_keepalive_timeout_total 1533
telemt_me_reconnect_attempts_total 63479
telemt_me_reconnect_success_total 63378
telemt_me_reader_eof_total 65030
telemt_me_idle_close_by_peer_total 65029
telemt_me_route_drop_no_conn_total 185185
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 270
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1047
telemt_desync_full_logged_total 317
telemt_desync_suppressed_total 730
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 429
telemt_desync_frames_bucket_total{bucket="gt_10"} 419
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 65110
telemt_me_writer_restored_same_endpoint_total 63353
telemt_me_writer_removed_unexpected_minus_restored_total 1757
telemt_user_connections_total{user="hello"} 357028
telemt_user_connections_current{user="hello"} 469
telemt_user_octets_from_client{user="hello"} 5687751432 (5.30 GB)
telemt_user_octets_to_client{user="hello"} 113918763048 (106.10 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 64314.8 (17h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 914637
telemt_connections_bad_total 190786
telemt_handshake_timeouts_total 29765
telemt_upstream_connect_attempt_total 85437
telemt_upstream_connect_success_total 84869
telemt_upstream_connect_fail_total 274
telemt_upstream_connect_attempts_per_request{bucket="1"} 84868
telemt_upstream_connect_attempts_per_request{bucket="2"} 275
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50211
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34431
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 274
telemt_me_keepalive_timeout_total 1108
telemt_me_reconnect_attempts_total 38315
telemt_me_reconnect_success_total 38215
telemt_me_reader_eof_total 40216
telemt_me_idle_close_by_peer_total 40212
telemt_me_route_drop_no_conn_total 332178
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_single_endpoint_shadow_rotate_total 266
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1928
telemt_desync_full_logged_total 639
telemt_desync_suppressed_total 1289
telemt_desync_frames_bucket_total{bucket="1_2"} 595
telemt_desync_frames_bucket_total{bucket="3_10"} 621
telemt_desync_frames_bucket_total{bucket="gt_10"} 712
telemt_pool_swap_total 7
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 40228
telemt_me_writer_restored_same_endpoint_total 38193
telemt_me_writer_removed_unexpected_minus_restored_total 2035
telemt_user_connections_total{user="hello"} 649520
telemt_user_connections_current{user="hello"} 891
telemt_user_octets_from_client{user="hello"} 13187071724 (12.28 GB)
telemt_user_octets_to_client{user="hello"} 220305096160 (205.18 GB)
telemt_user_unique_ips_current{user="hello"} 72
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 10992.0 (3h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164058
telemt_connections_bad_total 16005
telemt_handshake_timeouts_total 5211
telemt_upstream_connect_attempt_total 4970
telemt_upstream_connect_success_total 4970
telemt_upstream_connect_attempts_per_request{bucket="1"} 4970
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1970
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 855
telemt_me_reconnect_success_total 867
telemt_me_reader_eof_total 874
telemt_me_idle_close_by_peer_total 874
telemt_me_route_drop_no_conn_total 53548
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 48
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 189
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 117
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 3
telemt_pool_force_close_total 110
telemt_me_writer_removed_unexpected_total 874
telemt_me_writer_restored_same_endpoint_total 846
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 137582
telemt_user_connections_current{user="hello"} 552
telemt_user_octets_from_client{user="hello"} 1836931960 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 62964179848 (58.64 GB)
telemt_user_unique_ips_current{user="hello"} 56
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 11351.5 (3h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194183
telemt_connections_bad_total 1858
telemt_handshake_timeouts_total 3142
telemt_upstream_connect_attempt_total 6189
telemt_upstream_connect_success_total 6158
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 6158
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2565
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 1247
telemt_me_reconnect_success_total 1255
telemt_me_reader_eof_total 1280
telemt_me_idle_close_by_peer_total 1280
telemt_me_route_drop_no_conn_total 71106
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 48
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 467
telemt_desync_full_logged_total 178
telemt_desync_suppressed_total 289
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 200
telemt_desync_frames_bucket_total{bucket="gt_10"} 203
telemt_pool_swap_total 2
telemt_pool_force_close_total 101
telemt_me_writer_removed_unexpected_total 1280
telemt_me_writer_restored_same_endpoint_total 1235
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 168542
telemt_user_connections_current{user="hello"} 612
telemt_user_octets_from_client{user="hello"} 2753422260 (2.56 GB)
telemt_user_octets_to_client{user="hello"} 46664062496 (43.46 GB)
telemt_user_unique_ips_current{user="hello"} 56
```