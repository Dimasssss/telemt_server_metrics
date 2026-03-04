# Server Metrics 2026-03-04 11:06:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 50173.2 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 787306
telemt_connections_bad_total 11431
telemt_handshake_timeouts_total 10018
telemt_upstream_connect_attempt_total 31885
telemt_upstream_connect_success_total 31751
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 31751
telemt_upstream_connect_attempts_per_request{bucket="2"} 57
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14159
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 353
telemt_me_reconnect_attempts_total 7076
telemt_me_reconnect_success_total 7031
telemt_me_reader_eof_total 7250
telemt_me_idle_close_by_peer_total 7250
telemt_me_route_drop_no_conn_total 306395
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 197
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1282
telemt_desync_full_logged_total 437
telemt_desync_suppressed_total 845
telemt_desync_frames_bucket_total{bucket="1_2"} 353
telemt_desync_frames_bucket_total{bucket="3_10"} 495
telemt_desync_frames_bucket_total{bucket="gt_10"} 434
telemt_pool_swap_total 12
telemt_pool_force_close_total 492
telemt_pool_stale_pick_total 58
telemt_me_writer_removed_unexpected_total 7250
telemt_me_writer_restored_same_endpoint_total 7010
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 639428
telemt_user_connections_current{user="hello"} 913
telemt_user_octets_from_client{user="hello"} 7070053192 (6.58 GB)
telemt_user_octets_to_client{user="hello"} 193028265428 (179.77 GB)
telemt_user_unique_ips_current{user="hello"} 81
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 50169.6 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307541
telemt_connections_bad_total 2784
telemt_handshake_timeouts_total 27154
telemt_upstream_connect_attempt_total 96946
telemt_upstream_connect_success_total 95494
telemt_upstream_connect_fail_total 688
telemt_upstream_connect_attempts_per_request{bucket="1"} 95488
telemt_upstream_connect_attempts_per_request{bucket="2"} 694
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31461
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 688
telemt_me_keepalive_timeout_total 1363
telemt_me_reconnect_attempts_total 55038
telemt_me_reconnect_success_total 54952
telemt_me_reader_eof_total 56360
telemt_me_idle_close_by_peer_total 56359
telemt_me_route_drop_no_conn_total 135809
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 212
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 584
telemt_desync_full_logged_total 206
telemt_desync_suppressed_total 378
telemt_desync_frames_bucket_total{bucket="1_2"} 115
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 212
telemt_pool_swap_total 3
telemt_pool_force_close_total 216
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 56440
telemt_me_writer_restored_same_endpoint_total 54927
telemt_me_writer_removed_unexpected_minus_restored_total 1513
telemt_user_connections_total{user="hello"} 238206
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 2872208772 (2.67 GB)
telemt_user_octets_to_client{user="hello"} 77834084676 (72.49 GB)
telemt_user_unique_ips_current{user="hello"} 37
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 50168.5 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 606128
telemt_connections_bad_total 151322
telemt_handshake_timeouts_total 18391
telemt_upstream_connect_attempt_total 75358
telemt_upstream_connect_success_total 74917
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 74916
telemt_upstream_connect_attempts_per_request{bucket="2"} 212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30895
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_timeout_total 969
telemt_me_reconnect_attempts_total 35253
telemt_me_reconnect_success_total 35165
telemt_me_reader_eof_total 37060
telemt_me_idle_close_by_peer_total 37056
telemt_me_route_drop_no_conn_total 224266
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 209
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1050
telemt_desync_full_logged_total 382
telemt_desync_suppressed_total 668
telemt_desync_frames_bucket_total{bucket="1_2"} 327
telemt_desync_frames_bucket_total{bucket="3_10"} 344
telemt_desync_frames_bucket_total{bucket="gt_10"} 379
telemt_pool_swap_total 4
telemt_pool_force_close_total 201
telemt_me_writer_removed_unexpected_total 37072
telemt_me_writer_restored_same_endpoint_total 35144
telemt_me_writer_removed_unexpected_minus_restored_total 1928
telemt_user_connections_total{user="hello"} 417518
telemt_user_connections_current{user="hello"} 659
telemt_user_octets_from_client{user="hello"} 5277763916 (4.92 GB)
telemt_user_octets_to_client{user="hello"} 140936608436 (131.26 GB)
telemt_user_unique_ips_current{user="hello"} 55
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 50167.4 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 395418
telemt_connections_bad_total 27261
telemt_handshake_timeouts_total 66227
telemt_upstream_connect_attempt_total 37376
telemt_upstream_connect_success_total 37229
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 37229
telemt_upstream_connect_attempts_per_request{bucket="2"} 72
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14122
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 419
telemt_me_reconnect_attempts_total 7938
telemt_me_reconnect_success_total 7912
telemt_me_reader_eof_total 8077
telemt_me_idle_close_by_peer_total 8077
telemt_me_route_drop_no_conn_total 111608
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 207
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 221
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 131
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 13
telemt_pool_force_close_total 317
telemt_me_writer_removed_unexpected_total 8077
telemt_me_writer_restored_same_endpoint_total 7891
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 279942
telemt_user_connections_current{user="hello"} 455
telemt_user_octets_from_client{user="hello"} 3338213244 (3.11 GB)
telemt_user_octets_to_client{user="hello"} 101652982556 (94.67 GB)
telemt_user_unique_ips_current{user="hello"} 32
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 50166.2 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 533645
telemt_connections_bad_total 6813
telemt_handshake_timeouts_total 132395
telemt_upstream_connect_attempt_total 71416
telemt_upstream_connect_success_total 70931
telemt_upstream_connect_fail_total 230
telemt_upstream_connect_attempts_per_request{bucket="1"} 70931
telemt_upstream_connect_attempts_per_request{bucket="2"} 230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27932
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 192
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 230
telemt_me_keepalive_timeout_total 929
telemt_me_reconnect_attempts_total 34454
telemt_me_reconnect_success_total 34422
telemt_me_reader_eof_total 36121
telemt_me_idle_close_by_peer_total 36120
telemt_me_route_drop_no_conn_total 168090
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 211
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 651
telemt_desync_full_logged_total 213
telemt_desync_suppressed_total 438
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 290
telemt_desync_frames_bucket_total{bucket="gt_10"} 239
telemt_pool_swap_total 6
telemt_pool_force_close_total 263
telemt_pool_stale_pick_total 2870
telemt_me_writer_removed_unexpected_total 36133
telemt_me_writer_restored_same_endpoint_total 34397
telemt_me_writer_removed_unexpected_minus_restored_total 1736
telemt_user_connections_total{user="hello"} 370261
telemt_user_connections_current{user="hello"} 524
telemt_user_octets_from_client{user="hello"} 4828222576 (4.50 GB)
telemt_user_octets_to_client{user="hello"} 99354927380 (92.53 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 44
```