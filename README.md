# Server Metrics 2026-03-04 09:39:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 44943.8 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 613099
telemt_connections_bad_total 10944
telemt_handshake_timeouts_total 7133
telemt_upstream_connect_attempt_total 29408
telemt_upstream_connect_success_total 29282
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 29282
telemt_upstream_connect_attempts_per_request{bucket="2"} 53
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12971
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 311
telemt_me_reconnect_attempts_total 6466
telemt_me_reconnect_success_total 6424
telemt_me_reader_eof_total 6617
telemt_me_idle_close_by_peer_total 6617
telemt_me_route_drop_no_conn_total 216758
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 179
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1071
telemt_desync_full_logged_total 374
telemt_desync_suppressed_total 697
telemt_desync_frames_bucket_total{bucket="1_2"} 305
telemt_desync_frames_bucket_total{bucket="3_10"} 400
telemt_desync_frames_bucket_total{bucket="gt_10"} 366
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 6617
telemt_me_writer_restored_same_endpoint_total 6403
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 506406
telemt_user_connections_current{user="hello"} 987
telemt_user_octets_from_client{user="hello"} 5593964068 (5.21 GB)
telemt_user_octets_to_client{user="hello"} 148224078232 (138.04 GB)
telemt_user_unique_ips_current{user="hello"} 89
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 44940.2 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 241902
telemt_connections_bad_total 2020
telemt_handshake_timeouts_total 25478
telemt_upstream_connect_attempt_total 93180
telemt_upstream_connect_success_total 91876
telemt_upstream_connect_fail_total 614
telemt_upstream_connect_attempts_per_request{bucket="1"} 91870
telemt_upstream_connect_attempts_per_request{bucket="2"} 620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30109
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 614
telemt_me_keepalive_timeout_total 1323
telemt_me_reconnect_attempts_total 54017
telemt_me_reconnect_success_total 53935
telemt_me_reader_eof_total 55311
telemt_me_idle_close_by_peer_total 55310
telemt_me_route_drop_no_conn_total 115039
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 192
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 518
telemt_desync_full_logged_total 186
telemt_desync_suppressed_total 332
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 2
telemt_pool_force_close_total 140
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 55391
telemt_me_writer_restored_same_endpoint_total 53910
telemt_me_writer_removed_unexpected_minus_restored_total 1481
telemt_user_connections_total{user="hello"} 184944
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 2115093912 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 64175361940 (59.77 GB)
telemt_user_unique_ips_current{user="hello"} 37
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 44939.1 (12h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 502880
telemt_connections_bad_total 137827
telemt_handshake_timeouts_total 15197
telemt_upstream_connect_attempt_total 64534
telemt_upstream_connect_success_total 64129
telemt_upstream_connect_fail_total 193
telemt_upstream_connect_attempts_per_request{bucket="1"} 64128
telemt_upstream_connect_attempts_per_request{bucket="2"} 194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26809
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 193
telemt_me_keepalive_timeout_total 859
telemt_me_reconnect_attempts_total 29099
telemt_me_reconnect_success_total 29020
telemt_me_reader_eof_total 30608
telemt_me_idle_close_by_peer_total 30605
telemt_me_route_drop_no_conn_total 169431
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 188
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 785
telemt_desync_full_logged_total 286
telemt_desync_suppressed_total 499
telemt_desync_frames_bucket_total{bucket="1_2"} 229
telemt_desync_frames_bucket_total{bucket="3_10"} 273
telemt_desync_frames_bucket_total{bucket="gt_10"} 283
telemt_pool_swap_total 4
telemt_pool_force_close_total 200
telemt_me_writer_removed_unexpected_total 30619
telemt_me_writer_restored_same_endpoint_total 28999
telemt_me_writer_removed_unexpected_minus_restored_total 1620
telemt_user_connections_total{user="hello"} 333940
telemt_user_connections_current{user="hello"} 577
telemt_user_octets_from_client{user="hello"} 3429658740 (3.19 GB)
telemt_user_octets_to_client{user="hello"} 119561650484 (111.35 GB)
telemt_user_unique_ips_current{user="hello"} 68
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 44938.0 (12h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 323210
telemt_connections_bad_total 22539
telemt_handshake_timeouts_total 52295
telemt_upstream_connect_attempt_total 32652
telemt_upstream_connect_success_total 32521
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 32521
telemt_upstream_connect_attempts_per_request{bucket="2"} 64
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 373
telemt_me_reconnect_attempts_total 6587
telemt_me_reconnect_success_total 6566
telemt_me_reader_eof_total 6691
telemt_me_idle_close_by_peer_total 6691
telemt_me_route_drop_no_conn_total 91561
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
telemt_pool_force_close_total 315
telemt_me_writer_removed_unexpected_total 6691
telemt_me_writer_restored_same_endpoint_total 6545
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 227326
telemt_user_connections_current{user="hello"} 402
telemt_user_octets_from_client{user="hello"} 2547193116 (2.37 GB)
telemt_user_octets_to_client{user="hello"} 78743395368 (73.34 GB)
telemt_user_unique_ips_current{user="hello"} 40
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 44936.9 (12h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 453417
telemt_connections_bad_total 6487
telemt_handshake_timeouts_total 132142
telemt_upstream_connect_attempt_total 68053
telemt_upstream_connect_success_total 67628
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 67628
telemt_upstream_connect_attempts_per_request{bucket="2"} 200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26827
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_keepalive_timeout_total 896
telemt_me_reconnect_attempts_total 33512
telemt_me_reconnect_success_total 33483
telemt_me_reader_eof_total 35161
telemt_me_idle_close_by_peer_total 35160
telemt_me_route_drop_no_conn_total 138012
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 188
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 397
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 269
telemt_desync_frames_bucket_total{bucket="1_2"} 70
telemt_desync_frames_bucket_total{bucket="3_10"} 191
telemt_desync_frames_bucket_total{bucket="gt_10"} 136
telemt_pool_swap_total 5
telemt_pool_force_close_total 233
telemt_pool_stale_pick_total 2867
telemt_me_writer_removed_unexpected_total 35173
telemt_me_writer_restored_same_endpoint_total 33458
telemt_me_writer_removed_unexpected_minus_restored_total 1715
telemt_user_connections_total{user="hello"} 295267
telemt_user_connections_current{user="hello"} 533
telemt_user_octets_from_client{user="hello"} 4213027832 (3.92 GB)
telemt_user_octets_to_client{user="hello"} 73613905504 (68.56 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 56
```