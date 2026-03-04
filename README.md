# Server Metrics 2026-03-04 11:27:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 51402.1 (14h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 820560
telemt_connections_bad_total 11843
telemt_handshake_timeouts_total 11255
telemt_upstream_connect_attempt_total 32287
telemt_upstream_connect_success_total 32150
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 32150
telemt_upstream_connect_attempts_per_request{bucket="2"} 58
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14323
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 358
telemt_me_reconnect_attempts_total 7081
telemt_me_reconnect_success_total 7035
telemt_me_reader_eof_total 7254
telemt_me_idle_close_by_peer_total 7254
telemt_me_route_drop_no_conn_total 316981
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 202
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1343
telemt_desync_full_logged_total 454
telemt_desync_suppressed_total 889
telemt_desync_frames_bucket_total{bucket="1_2"} 375
telemt_desync_frames_bucket_total{bucket="3_10"} 520
telemt_desync_frames_bucket_total{bucket="gt_10"} 448
telemt_pool_swap_total 13
telemt_pool_force_close_total 492
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7254
telemt_me_writer_restored_same_endpoint_total 7014
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 664509
telemt_user_connections_current{user="hello"} 802
telemt_user_octets_from_client{user="hello"} 7267387432 (6.77 GB)
telemt_user_octets_to_client{user="hello"} 201348607948 (187.52 GB)
telemt_user_unique_ips_current{user="hello"} 89
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 51398.6 (14h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 326318
telemt_connections_bad_total 2923
telemt_handshake_timeouts_total 27260
telemt_upstream_connect_attempt_total 99040
telemt_upstream_connect_success_total 97544
telemt_upstream_connect_fail_total 710
telemt_upstream_connect_attempts_per_request{bucket="1"} 97538
telemt_upstream_connect_attempts_per_request{bucket="2"} 716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 710
telemt_me_keepalive_timeout_total 1376
telemt_me_reconnect_attempts_total 56037
telemt_me_reconnect_success_total 55951
telemt_me_reader_eof_total 57369
telemt_me_idle_close_by_peer_total 57368
telemt_me_route_drop_no_conn_total 139890
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 216
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 611
telemt_desync_full_logged_total 214
telemt_desync_suppressed_total 397
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 221
telemt_pool_swap_total 3
telemt_pool_force_close_total 216
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 57449
telemt_me_writer_restored_same_endpoint_total 55926
telemt_me_writer_removed_unexpected_minus_restored_total 1523
telemt_user_connections_total{user="hello"} 248682
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 3268451180 (3.04 GB)
telemt_user_octets_to_client{user="hello"} 80029850804 (74.53 GB)
telemt_user_unique_ips_current{user="hello"} 35
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 51397.4 (14h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 630248
telemt_connections_bad_total 154480
telemt_handshake_timeouts_total 19493
telemt_upstream_connect_attempt_total 78097
telemt_upstream_connect_success_total 77650
telemt_upstream_connect_fail_total 214
telemt_upstream_connect_attempts_per_request{bucket="1"} 77649
telemt_upstream_connect_attempts_per_request{bucket="2"} 215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31927
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 214
telemt_me_keepalive_timeout_total 1003
telemt_me_reconnect_attempts_total 36835
telemt_me_reconnect_success_total 36745
telemt_me_reader_eof_total 38713
telemt_me_idle_close_by_peer_total 38709
telemt_me_route_drop_no_conn_total 237815
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 213
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1129
telemt_desync_full_logged_total 402
telemt_desync_suppressed_total 727
telemt_desync_frames_bucket_total{bucket="1_2"} 342
telemt_desync_frames_bucket_total{bucket="3_10"} 375
telemt_desync_frames_bucket_total{bucket="gt_10"} 412
telemt_pool_swap_total 4
telemt_pool_force_close_total 201
telemt_me_writer_removed_unexpected_total 38725
telemt_me_writer_restored_same_endpoint_total 36724
telemt_me_writer_removed_unexpected_minus_restored_total 2001
telemt_user_connections_total{user="hello"} 437000
telemt_user_connections_current{user="hello"} 606
telemt_user_octets_from_client{user="hello"} 5742437860 (5.35 GB)
telemt_user_octets_to_client{user="hello"} 146810507784 (136.73 GB)
telemt_user_unique_ips_current{user="hello"} 64
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 51396.4 (14h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 409309
telemt_connections_bad_total 28364
telemt_handshake_timeouts_total 66440
telemt_upstream_connect_attempt_total 38156
telemt_upstream_connect_success_total 38004
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 38004
telemt_upstream_connect_attempts_per_request{bucket="2"} 74
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14453
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 428
telemt_me_reconnect_attempts_total 8212
telemt_me_reconnect_success_total 8184
telemt_me_reader_eof_total 8367
telemt_me_idle_close_by_peer_total 8367
telemt_me_route_drop_no_conn_total 116457
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 209
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 232
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 135
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 78
telemt_pool_swap_total 14
telemt_pool_force_close_total 375
telemt_me_writer_removed_unexpected_total 8367
telemt_me_writer_restored_same_endpoint_total 8163
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 292272
telemt_user_connections_current{user="hello"} 521
telemt_user_octets_from_client{user="hello"} 3597512320 (3.35 GB)
telemt_user_octets_to_client{user="hello"} 108875020384 (101.40 GB)
telemt_user_unique_ips_current{user="hello"} 57
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 51395.2 (14h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 551067
telemt_connections_bad_total 6815
telemt_handshake_timeouts_total 132443
telemt_upstream_connect_attempt_total 73014
telemt_upstream_connect_success_total 72517
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 72517
telemt_upstream_connect_attempts_per_request{bucket="2"} 235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28549
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 196
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_timeout_total 950
telemt_me_reconnect_attempts_total 35177
telemt_me_reconnect_success_total 35144
telemt_me_reader_eof_total 36862
telemt_me_idle_close_by_peer_total 36861
telemt_me_route_drop_no_conn_total 175224
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 215
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 765
telemt_desync_full_logged_total 240
telemt_desync_suppressed_total 525
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 324
telemt_desync_frames_bucket_total{bucket="gt_10"} 308
telemt_pool_swap_total 6
telemt_pool_force_close_total 263
telemt_pool_stale_pick_total 2870
telemt_me_writer_removed_unexpected_total 36874
telemt_me_writer_restored_same_endpoint_total 35119
telemt_me_writer_removed_unexpected_minus_restored_total 1755
telemt_user_connections_total{user="hello"} 387204
telemt_user_connections_current{user="hello"} 543
telemt_user_octets_from_client{user="hello"} 5073128492 (4.72 GB)
telemt_user_octets_to_client{user="hello"} 104757947904 (97.56 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 38
```