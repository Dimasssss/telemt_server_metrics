# Server Metrics 2026-03-04 08:53:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 42177.9 (11h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 512595
telemt_connections_bad_total 8091
telemt_handshake_timeouts_total 6637
telemt_upstream_connect_attempt_total 26333
telemt_upstream_connect_success_total 26218
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 26218
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11461
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 279
telemt_me_reconnect_attempts_total 5306
telemt_me_reconnect_success_total 5268
telemt_me_reader_eof_total 5404
telemt_me_idle_close_by_peer_total 5404
telemt_me_route_drop_no_conn_total 176730
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 168
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 936
telemt_desync_full_logged_total 339
telemt_desync_suppressed_total 597
telemt_desync_frames_bucket_total{bucket="1_2"} 272
telemt_desync_frames_bucket_total{bucket="3_10"} 351
telemt_desync_frames_bucket_total{bucket="gt_10"} 313
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 5404
telemt_me_writer_restored_same_endpoint_total 5247
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 434021
telemt_user_connections_current{user="hello"} 1068
telemt_user_octets_from_client{user="hello"} 5085837060 (4.74 GB)
telemt_user_octets_to_client{user="hello"} 130246663308 (121.30 GB)
telemt_user_unique_ips_current{user="hello"} 115
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 42174.5 (11h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211569
telemt_connections_bad_total 1947
telemt_handshake_timeouts_total 24266
telemt_upstream_connect_attempt_total 87144
telemt_upstream_connect_success_total 85890
telemt_upstream_connect_fail_total 589
telemt_upstream_connect_attempts_per_request{bucket="1"} 85884
telemt_upstream_connect_attempts_per_request{bucket="2"} 595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27806
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 589
telemt_me_keepalive_timeout_total 1261
telemt_me_reconnect_attempts_total 50689
telemt_me_reconnect_success_total 50609
telemt_me_reader_eof_total 51903
telemt_me_idle_close_by_peer_total 51902
telemt_me_route_drop_no_conn_total 96236
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 180
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 476
telemt_desync_full_logged_total 167
telemt_desync_suppressed_total 309
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 219
telemt_desync_frames_bucket_total{bucket="gt_10"} 162
telemt_pool_swap_total 2
telemt_pool_force_close_total 139
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 51983
telemt_me_writer_restored_same_endpoint_total 50584
telemt_me_writer_removed_unexpected_minus_restored_total 1399
telemt_user_connections_total{user="hello"} 157346
telemt_user_connections_current{user="hello"} 426
telemt_user_octets_from_client{user="hello"} 1924721836 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 57331771900 (53.39 GB)
telemt_user_unique_ips_current{user="hello"} 40
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 42173.2 (11h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 435756
telemt_connections_bad_total 124490
telemt_handshake_timeouts_total 12587
telemt_upstream_connect_attempt_total 61553
telemt_upstream_connect_success_total 61173
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 61172
telemt_upstream_connect_attempts_per_request{bucket="2"} 182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25867
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_keepalive_timeout_total 820
telemt_me_reconnect_attempts_total 28008
telemt_me_reconnect_success_total 27935
telemt_me_reader_eof_total 29489
telemt_me_idle_close_by_peer_total 29486
telemt_me_route_drop_no_conn_total 144352
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 177
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 667
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 418
telemt_desync_frames_bucket_total{bucket="1_2"} 190
telemt_desync_frames_bucket_total{bucket="3_10"} 234
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 4
telemt_pool_force_close_total 199
telemt_me_writer_removed_unexpected_total 29500
telemt_me_writer_restored_same_endpoint_total 27914
telemt_me_writer_removed_unexpected_minus_restored_total 1586
telemt_user_connections_total{user="hello"} 283388
telemt_user_connections_current{user="hello"} 588
telemt_user_octets_from_client{user="hello"} 2773091192 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 107747350692 (100.35 GB)
telemt_user_unique_ips_current{user="hello"} 68
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 42172.2 (11h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257145
telemt_connections_bad_total 20057
telemt_handshake_timeouts_total 19867
telemt_upstream_connect_attempt_total 31393
telemt_upstream_connect_success_total 31264
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 31264
telemt_upstream_connect_attempts_per_request{bucket="2"} 63
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11836
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 356
telemt_me_reconnect_attempts_total 6528
telemt_me_reconnect_success_total 6509
telemt_me_reader_eof_total 6634
telemt_me_idle_close_by_peer_total 6634
telemt_me_route_drop_no_conn_total 79736
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 174
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 168
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 12
telemt_pool_force_close_total 292
telemt_me_writer_removed_unexpected_total 6634
telemt_me_writer_restored_same_endpoint_total 6488
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 196532
telemt_user_connections_current{user="hello"} 370
telemt_user_octets_from_client{user="hello"} 2194866696 (2.04 GB)
telemt_user_octets_to_client{user="hello"} 68895440024 (64.16 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 42170.9 (11h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 406927
telemt_connections_bad_total 6449
telemt_handshake_timeouts_total 132046
telemt_upstream_connect_attempt_total 64767
telemt_upstream_connect_success_total 64354
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 64354
telemt_upstream_connect_attempts_per_request{bucket="2"} 194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25503
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 174
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_keepalive_timeout_total 843
telemt_me_reconnect_attempts_total 31687
telemt_me_reconnect_success_total 31661
telemt_me_reader_eof_total 33263
telemt_me_idle_close_by_peer_total 33262
telemt_me_route_drop_no_conn_total 119351
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 179
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 270
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 177
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 132
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 4
telemt_pool_force_close_total 117
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 33276
telemt_me_writer_restored_same_endpoint_total 31636
telemt_me_writer_removed_unexpected_minus_restored_total 1640
telemt_user_connections_total{user="hello"} 253794
telemt_user_connections_current{user="hello"} 510
telemt_user_octets_from_client{user="hello"} 3712675412 (3.46 GB)
telemt_user_octets_to_client{user="hello"} 63072970768 (58.74 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 60
```