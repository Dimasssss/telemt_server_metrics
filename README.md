# Server Metrics 2026-03-04 09:29:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 44329.4 (12h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 596427
telemt_connections_bad_total 10796
telemt_handshake_timeouts_total 7024
telemt_upstream_connect_attempt_total 28687
telemt_upstream_connect_success_total 28562
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 28562
telemt_upstream_connect_attempts_per_request{bucket="2"} 53
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12595
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 308
telemt_me_reconnect_attempts_total 6188
telemt_me_reconnect_success_total 6147
telemt_me_reader_eof_total 6325
telemt_me_idle_close_by_peer_total 6325
telemt_me_route_drop_no_conn_total 208300
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 179
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1029
telemt_desync_full_logged_total 362
telemt_desync_suppressed_total 667
telemt_desync_frames_bucket_total{bucket="1_2"} 292
telemt_desync_frames_bucket_total{bucket="3_10"} 388
telemt_desync_frames_bucket_total{bucket="gt_10"} 349
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 6325
telemt_me_writer_restored_same_endpoint_total 6126
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 490837
telemt_user_connections_current{user="hello"} 940
telemt_user_octets_from_client{user="hello"} 5514937064 (5.14 GB)
telemt_user_octets_to_client{user="hello"} 144373524776 (134.46 GB)
telemt_user_unique_ips_current{user="hello"} 87
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 44325.9 (12h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 234608
telemt_connections_bad_total 2019
telemt_handshake_timeouts_total 24819
telemt_upstream_connect_attempt_total 91703
telemt_upstream_connect_success_total 90405
telemt_upstream_connect_fail_total 611
telemt_upstream_connect_attempts_per_request{bucket="1"} 90399
telemt_upstream_connect_attempts_per_request{bucket="2"} 617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29574
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 611
telemt_me_keepalive_timeout_total 1301
telemt_me_reconnect_attempts_total 53142
telemt_me_reconnect_success_total 53061
telemt_me_reader_eof_total 54419
telemt_me_idle_close_by_peer_total 54418
telemt_me_route_drop_no_conn_total 110955
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 189
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 515
telemt_desync_full_logged_total 183
telemt_desync_suppressed_total 332
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 232
telemt_desync_frames_bucket_total{bucket="gt_10"} 182
telemt_pool_swap_total 2
telemt_pool_force_close_total 140
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 54499
telemt_me_writer_restored_same_endpoint_total 53036
telemt_me_writer_removed_unexpected_minus_restored_total 1463
telemt_user_connections_total{user="hello"} 179154
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 2071303960 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 62581970004 (58.28 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 44324.6 (12h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 490169
telemt_connections_bad_total 136050
telemt_handshake_timeouts_total 14749
telemt_upstream_connect_attempt_total 63660
telemt_upstream_connect_success_total 63255
telemt_upstream_connect_fail_total 193
telemt_upstream_connect_attempts_per_request{bucket="1"} 63254
telemt_upstream_connect_attempts_per_request{bucket="2"} 194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26511
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 193
telemt_me_keepalive_timeout_total 844
telemt_me_reconnect_attempts_total 28652
telemt_me_reconnect_success_total 28575
telemt_me_reader_eof_total 30148
telemt_me_idle_close_by_peer_total 30145
telemt_me_route_drop_no_conn_total 163872
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 187
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 752
telemt_desync_full_logged_total 276
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 220
telemt_desync_frames_bucket_total{bucket="3_10"} 263
telemt_desync_frames_bucket_total{bucket="gt_10"} 269
telemt_pool_swap_total 4
telemt_pool_force_close_total 200
telemt_me_writer_removed_unexpected_total 30159
telemt_me_writer_restored_same_endpoint_total 28554
telemt_me_writer_removed_unexpected_minus_restored_total 1605
telemt_user_connections_total{user="hello"} 323501
telemt_user_connections_current{user="hello"} 616
telemt_user_octets_from_client{user="hello"} 3177450560 (2.96 GB)
telemt_user_octets_to_client{user="hello"} 116564195472 (108.56 GB)
telemt_user_unique_ips_current{user="hello"} 68
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 44323.7 (12h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 313887
telemt_connections_bad_total 21974
telemt_handshake_timeouts_total 50431
telemt_upstream_connect_attempt_total 32501
telemt_upstream_connect_success_total 32370
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 32370
telemt_upstream_connect_attempts_per_request{bucket="2"} 64
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12226
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 369
telemt_me_reconnect_attempts_total 6585
telemt_me_reconnect_success_total 6564
telemt_me_reader_eof_total 6689
telemt_me_idle_close_by_peer_total 6689
telemt_me_route_drop_no_conn_total 89248
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 184
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 173
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 98
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 13
telemt_pool_force_close_total 292
telemt_me_writer_removed_unexpected_total 6689
telemt_me_writer_restored_same_endpoint_total 6543
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 220526
telemt_user_connections_current{user="hello"} 315
telemt_user_octets_from_client{user="hello"} 2436558868 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 76731264540 (71.46 GB)
telemt_user_unique_ips_current{user="hello"} 38
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 44322.4 (12h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 442535
telemt_connections_bad_total 6487
telemt_handshake_timeouts_total 132139
telemt_upstream_connect_attempt_total 67837
telemt_upstream_connect_success_total 67412
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 67412
telemt_upstream_connect_attempts_per_request{bucket="2"} 200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26752
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_keepalive_timeout_total 893
telemt_me_reconnect_attempts_total 33507
telemt_me_reconnect_success_total 33479
telemt_me_reader_eof_total 35156
telemt_me_idle_close_by_peer_total 35155
telemt_me_route_drop_no_conn_total 134875
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 188
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 375
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 253
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 5
telemt_pool_force_close_total 233
telemt_pool_stale_pick_total 2838
telemt_me_writer_removed_unexpected_total 35168
telemt_me_writer_restored_same_endpoint_total 33454
telemt_me_writer_removed_unexpected_minus_restored_total 1714
telemt_user_connections_total{user="hello"} 286377
telemt_user_connections_current{user="hello"} 511
telemt_user_octets_from_client{user="hello"} 3988152364 (3.71 GB)
telemt_user_octets_to_client{user="hello"} 71093063716 (66.21 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 43
```