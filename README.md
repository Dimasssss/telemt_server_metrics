# Server Metrics 2026-03-04 10:10:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 46793.2 (12h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 671244
telemt_connections_bad_total 10946
telemt_handshake_timeouts_total 7453
telemt_upstream_connect_attempt_total 30882
telemt_upstream_connect_success_total 30754
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 30754
telemt_upstream_connect_attempts_per_request{bucket="2"} 54
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13690
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 332
telemt_me_reconnect_attempts_total 7045
telemt_me_reconnect_success_total 7001
telemt_me_reader_eof_total 7220
telemt_me_idle_close_by_peer_total 7220
telemt_me_route_drop_no_conn_total 238731
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 185
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1168
telemt_desync_full_logged_total 404
telemt_desync_suppressed_total 764
telemt_desync_frames_bucket_total{bucket="1_2"} 322
telemt_desync_frames_bucket_total{bucket="3_10"} 447
telemt_desync_frames_bucket_total{bucket="gt_10"} 399
telemt_pool_swap_total 10
telemt_pool_force_close_total 430
telemt_me_writer_removed_unexpected_total 7220
telemt_me_writer_restored_same_endpoint_total 6980
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 553145
telemt_user_connections_current{user="hello"} 964
telemt_user_octets_from_client{user="hello"} 6202247076 (5.78 GB)
telemt_user_octets_to_client{user="hello"} 164122745828 (152.85 GB)
telemt_user_unique_ips_current{user="hello"} 107
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 46789.8 (12h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 271267
telemt_connections_bad_total 2509
telemt_handshake_timeouts_total 26379
telemt_upstream_connect_attempt_total 93971
telemt_upstream_connect_success_total 92625
telemt_upstream_connect_fail_total 635
telemt_upstream_connect_attempts_per_request{bucket="1"} 92619
telemt_upstream_connect_attempts_per_request{bucket="2"} 641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30408
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 635
telemt_me_keepalive_timeout_total 1345
telemt_me_reconnect_attempts_total 54322
telemt_me_reconnect_success_total 54240
telemt_me_reader_eof_total 55638
telemt_me_idle_close_by_peer_total 55637
telemt_me_route_drop_no_conn_total 123295
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 198
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 542
telemt_desync_full_logged_total 195
telemt_desync_suppressed_total 347
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 193
telemt_pool_swap_total 3
telemt_pool_force_close_total 216
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 55718
telemt_me_writer_restored_same_endpoint_total 54215
telemt_me_writer_removed_unexpected_minus_restored_total 1503
telemt_user_connections_total{user="hello"} 208480
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 2575544520 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 69333224516 (64.57 GB)
telemt_user_unique_ips_current{user="hello"} 36
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 46788.6 (12h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 542331
telemt_connections_bad_total 142597
telemt_handshake_timeouts_total 16460
telemt_upstream_connect_attempt_total 67758
telemt_upstream_connect_success_total 67338
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 67337
telemt_upstream_connect_attempts_per_request{bucket="2"} 201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28007
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 190
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_keepalive_timeout_total 893
telemt_me_reconnect_attempts_total 30811
telemt_me_reconnect_success_total 30728
telemt_me_reader_eof_total 32391
telemt_me_idle_close_by_peer_total 32388
telemt_me_route_drop_no_conn_total 189026
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 196
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 887
telemt_desync_full_logged_total 323
telemt_desync_suppressed_total 564
telemt_desync_frames_bucket_total{bucket="1_2"} 263
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 322
telemt_pool_swap_total 4
telemt_pool_force_close_total 201
telemt_me_writer_removed_unexpected_total 32402
telemt_me_writer_restored_same_endpoint_total 30707
telemt_me_writer_removed_unexpected_minus_restored_total 1695
telemt_user_connections_total{user="hello"} 366209
telemt_user_connections_current{user="hello"} 634
telemt_user_octets_from_client{user="hello"} 3961066216 (3.69 GB)
telemt_user_octets_to_client{user="hello"} 129363877772 (120.48 GB)
telemt_user_unique_ips_current{user="hello"} 70
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 46787.6 (12h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 348473
telemt_connections_bad_total 24239
telemt_handshake_timeouts_total 55043
telemt_upstream_connect_attempt_total 33542
telemt_upstream_connect_success_total 33403
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 33403
telemt_upstream_connect_attempts_per_request{bucket="2"} 68
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12598
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 381
telemt_me_reconnect_attempts_total 6703
telemt_me_reconnect_success_total 6680
telemt_me_reader_eof_total 6809
telemt_me_idle_close_by_peer_total 6809
telemt_me_route_drop_no_conn_total 99008
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 191
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 196
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 116
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 90
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 13
telemt_pool_force_close_total 315
telemt_me_writer_removed_unexpected_total 6809
telemt_me_writer_restored_same_endpoint_total 6659
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 247771
telemt_user_connections_current{user="hello"} 405
telemt_user_octets_from_client{user="hello"} 2690577768 (2.51 GB)
telemt_user_octets_to_client{user="hello"} 86601708200 (80.65 GB)
telemt_user_unique_ips_current{user="hello"} 50
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 46786.2 (12h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 482134
telemt_connections_bad_total 6568
telemt_handshake_timeouts_total 132182
telemt_upstream_connect_attempt_total 68555
telemt_upstream_connect_success_total 68108
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 68108
telemt_upstream_connect_attempts_per_request{bucket="2"} 211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27031
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 187
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_timeout_total 900
telemt_me_reconnect_attempts_total 33523
telemt_me_reconnect_success_total 33491
telemt_me_reader_eof_total 35170
telemt_me_idle_close_by_peer_total 35169
telemt_me_route_drop_no_conn_total 149420
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 195
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 488
telemt_desync_full_logged_total 154
telemt_desync_suppressed_total 334
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 227
telemt_desync_frames_bucket_total{bucket="gt_10"} 163
telemt_pool_swap_total 6
telemt_pool_force_close_total 262
telemt_pool_stale_pick_total 2870
telemt_me_writer_removed_unexpected_total 35182
telemt_me_writer_restored_same_endpoint_total 33466
telemt_me_writer_removed_unexpected_minus_restored_total 1716
telemt_user_connections_total{user="hello"} 323096
telemt_user_connections_current{user="hello"} 554
telemt_user_octets_from_client{user="hello"} 4438362864 (4.13 GB)
telemt_user_octets_to_client{user="hello"} 80759631392 (75.21 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 60
```