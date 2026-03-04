# Server Metrics 2026-03-04 08:43:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 41560.1 (11h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 494577
telemt_connections_bad_total 8061
telemt_handshake_timeouts_total 6592
telemt_upstream_connect_attempt_total 25774
telemt_upstream_connect_success_total 25661
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 25661
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11179
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 270
telemt_me_reconnect_attempts_total 5104
telemt_me_reconnect_success_total 5067
telemt_me_reader_eof_total 5191
telemt_me_idle_close_by_peer_total 5191
telemt_me_route_drop_no_conn_total 168203
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 168
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 908
telemt_desync_full_logged_total 331
telemt_desync_suppressed_total 577
telemt_desync_frames_bucket_total{bucket="1_2"} 264
telemt_desync_frames_bucket_total{bucket="3_10"} 340
telemt_desync_frames_bucket_total{bucket="gt_10"} 304
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 5191
telemt_me_writer_restored_same_endpoint_total 5046
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 419487
telemt_user_connections_current{user="hello"} 882
telemt_user_octets_from_client{user="hello"} 4944812760 (4.61 GB)
telemt_user_octets_to_client{user="hello"} 125467497500 (116.85 GB)
telemt_user_unique_ips_current{user="hello"} 87
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 41556.7 (11h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205101
telemt_connections_bad_total 1904
telemt_handshake_timeouts_total 24206
telemt_upstream_connect_attempt_total 85690
telemt_upstream_connect_success_total 84453
telemt_upstream_connect_fail_total 580
telemt_upstream_connect_attempts_per_request{bucket="1"} 84447
telemt_upstream_connect_attempts_per_request{bucket="2"} 586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27307
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 580
telemt_me_keepalive_timeout_total 1253
telemt_me_reconnect_attempts_total 49843
telemt_me_reconnect_success_total 49763
telemt_me_reader_eof_total 51021
telemt_me_idle_close_by_peer_total 51020
telemt_me_route_drop_no_conn_total 91346
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 178
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 470
telemt_desync_full_logged_total 166
telemt_desync_suppressed_total 304
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 215
telemt_desync_frames_bucket_total{bucket="gt_10"} 160
telemt_pool_swap_total 2
telemt_pool_force_close_total 139
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 51101
telemt_me_writer_restored_same_endpoint_total 49738
telemt_me_writer_removed_unexpected_minus_restored_total 1363
telemt_user_connections_total{user="hello"} 151355
telemt_user_connections_current{user="hello"} 337
telemt_user_octets_from_client{user="hello"} 1863211708 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 55984424876 (52.14 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 41555.4 (11h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 423437
telemt_connections_bad_total 121874
telemt_handshake_timeouts_total 12099
telemt_upstream_connect_attempt_total 61042
telemt_upstream_connect_success_total 60664
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 60663
telemt_upstream_connect_attempts_per_request{bucket="2"} 180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25716
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 815
telemt_me_reconnect_attempts_total 27882
telemt_me_reconnect_success_total 27810
telemt_me_reader_eof_total 29362
telemt_me_idle_close_by_peer_total 29359
telemt_me_route_drop_no_conn_total 140203
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 175
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 649
telemt_desync_full_logged_total 244
telemt_desync_suppressed_total 405
telemt_desync_frames_bucket_total{bucket="1_2"} 187
telemt_desync_frames_bucket_total{bucket="3_10"} 231
telemt_desync_frames_bucket_total{bucket="gt_10"} 231
telemt_pool_swap_total 4
telemt_pool_force_close_total 199
telemt_me_writer_removed_unexpected_total 29373
telemt_me_writer_restored_same_endpoint_total 27789
telemt_me_writer_removed_unexpected_minus_restored_total 1584
telemt_user_connections_total{user="hello"} 274191
telemt_user_connections_current{user="hello"} 482
telemt_user_octets_from_client{user="hello"} 2681946716 (2.50 GB)
telemt_user_octets_to_client{user="hello"} 103645868840 (96.53 GB)
telemt_user_unique_ips_current{user="hello"} 51
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 41554.4 (11h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 240247
telemt_connections_bad_total 19503
telemt_handshake_timeouts_total 10900
telemt_upstream_connect_attempt_total 31282
telemt_upstream_connect_success_total 31153
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 31153
telemt_upstream_connect_attempts_per_request{bucket="2"} 63
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11791
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 355
telemt_me_reconnect_attempts_total 6525
telemt_me_reconnect_success_total 6507
telemt_me_reader_eof_total 6631
telemt_me_idle_close_by_peer_total 6631
telemt_me_route_drop_no_conn_total 77548
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 173
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 12
telemt_pool_force_close_total 261
telemt_me_writer_removed_unexpected_total 6631
telemt_me_writer_restored_same_endpoint_total 6486
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 189921
telemt_user_connections_current{user="hello"} 333
telemt_user_octets_from_client{user="hello"} 2127793752 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 67018129056 (62.42 GB)
telemt_user_unique_ips_current{user="hello"} 30
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 41552.9 (11h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 396736
telemt_connections_bad_total 6448
telemt_handshake_timeouts_total 132035
telemt_upstream_connect_attempt_total 62988
telemt_upstream_connect_success_total 62574
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 62574
telemt_upstream_connect_attempts_per_request{bucket="2"} 194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24819
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_keepalive_timeout_total 829
telemt_me_reconnect_attempts_total 30470
telemt_me_reconnect_success_total 30447
telemt_me_reader_eof_total 31987
telemt_me_idle_close_by_peer_total 31986
telemt_me_route_drop_no_conn_total 114513
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 177
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 263
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 173
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 4
telemt_pool_force_close_total 117
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 32000
telemt_me_writer_restored_same_endpoint_total 30422
telemt_me_writer_removed_unexpected_minus_restored_total 1578
telemt_user_connections_total{user="hello"} 245098
telemt_user_connections_current{user="hello"} 452
telemt_user_octets_from_client{user="hello"} 3168484812 (2.95 GB)
telemt_user_octets_to_client{user="hello"} 61124494900 (56.93 GB)
telemt_user_unique_ips_current{user="hello"} 34
```