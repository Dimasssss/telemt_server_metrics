# Server Metrics 2026-03-04 07:57:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 38795.0 (10h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 437319
telemt_connections_bad_total 7962
telemt_handshake_timeouts_total 6160
telemt_upstream_connect_attempt_total 24157
telemt_upstream_connect_success_total 24045
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 24045
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10382
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 14
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 257
telemt_me_reconnect_attempts_total 4778
telemt_me_reconnect_success_total 4746
telemt_me_reader_eof_total 4856
telemt_me_idle_close_by_peer_total 4856
telemt_me_route_drop_no_conn_total 146431
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 154
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 825
telemt_desync_full_logged_total 306
telemt_desync_suppressed_total 519
telemt_desync_frames_bucket_total{bucket="1_2"} 239
telemt_desync_frames_bucket_total{bucket="3_10"} 297
telemt_desync_frames_bucket_total{bucket="gt_10"} 289
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 4856
telemt_me_writer_restored_same_endpoint_total 4725
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 365812
telemt_user_connections_current{user="hello"} 946
telemt_user_octets_from_client{user="hello"} 4283633084 (3.99 GB)
telemt_user_octets_to_client{user="hello"} 109080439280 (101.59 GB)
telemt_user_unique_ips_current{user="hello"} 80
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 38788.8 (10h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183153
telemt_connections_bad_total 1626
telemt_handshake_timeouts_total 23555
telemt_upstream_connect_attempt_total 78955
telemt_upstream_connect_success_total 77815
telemt_upstream_connect_fail_total 532
telemt_upstream_connect_attempts_per_request{bucket="1"} 77809
telemt_upstream_connect_attempts_per_request{bucket="2"} 538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25047
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 532
telemt_me_keepalive_timeout_total 1207
telemt_me_reconnect_attempts_total 45810
telemt_me_reconnect_success_total 45733
telemt_me_reader_eof_total 46849
telemt_me_idle_close_by_peer_total 46848
telemt_me_route_drop_no_conn_total 72978
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 166
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 368
telemt_desync_full_logged_total 130
telemt_desync_suppressed_total 238
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 184
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 46929
telemt_me_writer_restored_same_endpoint_total 45708
telemt_me_writer_removed_unexpected_minus_restored_total 1221
telemt_user_connections_total{user="hello"} 130821
telemt_user_connections_current{user="hello"} 417
telemt_user_octets_from_client{user="hello"} 1369600896 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 51456152440 (47.92 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 38787.6 (10h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 365829
telemt_connections_bad_total 109150
telemt_handshake_timeouts_total 10828
telemt_upstream_connect_attempt_total 59478
telemt_upstream_connect_success_total 59136
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 59135
telemt_upstream_connect_attempts_per_request{bucket="2"} 163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 163
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_timeout_total 782
telemt_me_reconnect_attempts_total 27517
telemt_me_reconnect_success_total 27447
telemt_me_reader_eof_total 28980
telemt_me_idle_close_by_peer_total 28977
telemt_me_route_drop_no_conn_total 113221
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 163
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 562
telemt_desync_full_logged_total 213
telemt_desync_suppressed_total 349
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 208
telemt_desync_frames_bucket_total{bucket="gt_10"} 205
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 28991
telemt_me_writer_restored_same_endpoint_total 27426
telemt_me_writer_removed_unexpected_minus_restored_total 1565
telemt_user_connections_total{user="hello"} 234001
telemt_user_connections_current{user="hello"} 551
telemt_user_octets_from_client{user="hello"} 2206973204 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 84917292304 (79.09 GB)
telemt_user_unique_ips_current{user="hello"} 50
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 38786.5 (10h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208530
telemt_connections_bad_total 17009
telemt_handshake_timeouts_total 7808
telemt_upstream_connect_attempt_total 29336
telemt_upstream_connect_success_total 29214
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 29214
telemt_upstream_connect_attempts_per_request{bucket="2"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 332
telemt_me_reconnect_attempts_total 6253
telemt_me_reconnect_success_total 6238
telemt_me_reader_eof_total 6357
telemt_me_idle_close_by_peer_total 6357
telemt_me_route_drop_no_conn_total 68116
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 161
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 11
telemt_pool_force_close_total 261
telemt_me_writer_removed_unexpected_total 6357
telemt_me_writer_restored_same_endpoint_total 6217
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 164814
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 1713082396 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 58881445344 (54.84 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 38785.3 (10h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 354701
telemt_connections_bad_total 6429
telemt_handshake_timeouts_total 130704
telemt_upstream_connect_attempt_total 55978
telemt_upstream_connect_success_total 55588
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 55588
telemt_upstream_connect_attempts_per_request{bucket="2"} 182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22253
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 764
telemt_me_reconnect_attempts_total 26105
telemt_me_reconnect_success_total 26086
telemt_me_reader_eof_total 27453
telemt_me_idle_close_by_peer_total 27452
telemt_me_route_drop_no_conn_total 99789
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 165
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 239
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 157
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 119
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 4
telemt_pool_force_close_total 117
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 27467
telemt_me_writer_restored_same_endpoint_total 26061
telemt_me_writer_removed_unexpected_minus_restored_total 1406
telemt_user_connections_total{user="hello"} 210673
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 2684066716 (2.50 GB)
telemt_user_octets_to_client{user="hello"} 52033816500 (48.46 GB)
telemt_user_unique_ips_current{user="hello"} 37
```