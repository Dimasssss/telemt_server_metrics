# Server Metrics 2026-03-04 15:48:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 67085.3 (18h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1267818
telemt_connections_bad_total 16930
telemt_handshake_timeouts_total 22459
telemt_upstream_connect_attempt_total 38917
telemt_upstream_connect_success_total 38739
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 38739
telemt_upstream_connect_attempts_per_request{bucket="2"} 69
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17348
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 47
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 444
telemt_me_reconnect_attempts_total 8239
telemt_me_reconnect_success_total 8174
telemt_me_reader_eof_total 8444
telemt_me_idle_close_by_peer_total 8443
telemt_me_route_drop_no_conn_total 466855
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 262
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2552
telemt_desync_full_logged_total 821
telemt_desync_suppressed_total 1731
telemt_desync_frames_bucket_total{bucket="1_2"} 749
telemt_desync_frames_bucket_total{bucket="3_10"} 955
telemt_desync_frames_bucket_total{bucket="gt_10"} 848
telemt_pool_swap_total 17
telemt_pool_force_close_total 715
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8444
telemt_me_writer_restored_same_endpoint_total 8152
telemt_me_writer_removed_unexpected_minus_restored_total 292
telemt_user_connections_total{user="hello"} 1025445
telemt_user_connections_current{user="hello"} 1023
telemt_user_octets_from_client{user="hello"} 13619413064 (12.68 GB)
telemt_user_octets_to_client{user="hello"} 345633696900 (321.90 GB)
telemt_user_unique_ips_current{user="hello"} 72
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 67081.5 (18h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 481432
telemt_connections_bad_total 4190
telemt_handshake_timeouts_total 30506
telemt_upstream_connect_attempt_total 122270
telemt_upstream_connect_success_total 120532
telemt_upstream_connect_fail_total 831
telemt_upstream_connect_attempts_per_request{bucket="1"} 120526
telemt_upstream_connect_attempts_per_request{bucket="2"} 837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 78168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42340
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 831
telemt_me_keepalive_timeout_total 1601
telemt_me_reconnect_attempts_total 66785
telemt_me_reconnect_success_total 66680
telemt_me_reader_eof_total 68396
telemt_me_idle_close_by_peer_total 68395
telemt_me_route_drop_no_conn_total 195734
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 282
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1219
telemt_desync_full_logged_total 365
telemt_desync_suppressed_total 854
telemt_desync_frames_bucket_total{bucket="1_2"} 225
telemt_desync_frames_bucket_total{bucket="3_10"} 474
telemt_desync_frames_bucket_total{bucket="gt_10"} 520
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 68476
telemt_me_writer_restored_same_endpoint_total 66655
telemt_me_writer_removed_unexpected_minus_restored_total 1821
telemt_user_connections_total{user="hello"} 383141
telemt_user_connections_current{user="hello"} 408
telemt_user_octets_from_client{user="hello"} 5888743492 (5.48 GB)
telemt_user_octets_to_client{user="hello"} 121748739876 (113.39 GB)
telemt_user_unique_ips_current{user="hello"} 35
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 67080.3 (18h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 974572
telemt_connections_bad_total 198698
telemt_handshake_timeouts_total 30224
telemt_upstream_connect_attempt_total 88989
telemt_upstream_connect_success_total 88376
telemt_upstream_connect_fail_total 296
telemt_upstream_connect_attempts_per_request{bucket="1"} 88375
telemt_upstream_connect_attempts_per_request{bucket="2"} 297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35978
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 296
telemt_me_keepalive_timeout_total 1160
telemt_me_reconnect_attempts_total 39767
telemt_me_reconnect_success_total 39662
telemt_me_reader_eof_total 41746
telemt_me_idle_close_by_peer_total 41741
telemt_me_route_drop_no_conn_total 354074
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_single_endpoint_shadow_rotate_total 277
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2067
telemt_desync_full_logged_total 681
telemt_desync_suppressed_total 1386
telemt_desync_frames_bucket_total{bucket="1_2"} 625
telemt_desync_frames_bucket_total{bucket="3_10"} 667
telemt_desync_frames_bucket_total{bucket="gt_10"} 775
telemt_pool_swap_total 7
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 41759
telemt_me_writer_restored_same_endpoint_total 39640
telemt_me_writer_removed_unexpected_minus_restored_total 2119
telemt_user_connections_total{user="hello"} 699743
telemt_user_connections_current{user="hello"} 736
telemt_user_octets_from_client{user="hello"} 14084243376 (13.12 GB)
telemt_user_octets_to_client{user="hello"} 235802139356 (219.61 GB)
telemt_user_unique_ips_current{user="hello"} 71
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 13757.6 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217666
telemt_connections_bad_total 22810
telemt_handshake_timeouts_total 6145
telemt_upstream_connect_attempt_total 5584
telemt_upstream_connect_success_total 5584
telemt_upstream_connect_attempts_per_request{bucket="1"} 5584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2335
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 862
telemt_me_reconnect_success_total 872
telemt_me_reader_eof_total 880
telemt_me_idle_close_by_peer_total 880
telemt_me_route_drop_no_conn_total 66640
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 224
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 142
telemt_desync_frames_bucket_total{bucket="1_2"} 73
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 96
telemt_pool_swap_total 4
telemt_pool_force_close_total 146
telemt_me_writer_removed_unexpected_total 880
telemt_me_writer_restored_same_endpoint_total 851
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 180973
telemt_user_connections_current{user="hello"} 520
telemt_user_octets_from_client{user="hello"} 2291739608 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 71318973236 (66.42 GB)
telemt_user_unique_ips_current{user="hello"} 40
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 14117.1 (3h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 243423
telemt_connections_bad_total 2507
telemt_handshake_timeouts_total 3698
telemt_upstream_connect_attempt_total 7229
telemt_upstream_connect_success_total 7192
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 7192
telemt_upstream_connect_attempts_per_request{bucket="2"} 18
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3019
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 1313
telemt_me_reconnect_success_total 1320
telemt_me_reader_eof_total 1346
telemt_me_idle_close_by_peer_total 1346
telemt_me_route_drop_no_conn_total 91105
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 518
telemt_desync_full_logged_total 198
telemt_desync_suppressed_total 320
telemt_desync_frames_bucket_total{bucket="1_2"} 76
telemt_desync_frames_bucket_total{bucket="3_10"} 222
telemt_desync_frames_bucket_total{bucket="gt_10"} 220
telemt_pool_swap_total 3
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 1346
telemt_me_writer_restored_same_endpoint_total 1300
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 208327
telemt_user_connections_current{user="hello"} 606
telemt_user_octets_from_client{user="hello"} 3402234148 (3.17 GB)
telemt_user_octets_to_client{user="hello"} 61969136540 (57.71 GB)
telemt_user_unique_ips_current{user="hello"} 53
```