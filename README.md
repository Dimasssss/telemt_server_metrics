# Server Metrics 2026-03-04 11:17:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 50787.6 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 801543
telemt_connections_bad_total 11620
telemt_handshake_timeouts_total 10605
telemt_upstream_connect_attempt_total 32060
telemt_upstream_connect_success_total 31924
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 31924
telemt_upstream_connect_attempts_per_request{bucket="2"} 58
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14235
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 354
telemt_me_reconnect_attempts_total 7078
telemt_me_reconnect_success_total 7032
telemt_me_reader_eof_total 7251
telemt_me_idle_close_by_peer_total 7251
telemt_me_route_drop_no_conn_total 311850
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 201
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1314
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 870
telemt_desync_frames_bucket_total{bucket="1_2"} 367
telemt_desync_frames_bucket_total{bucket="3_10"} 506
telemt_desync_frames_bucket_total{bucket="gt_10"} 441
telemt_pool_swap_total 12
telemt_pool_force_close_total 492
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7251
telemt_me_writer_restored_same_endpoint_total 7011
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 651923
telemt_user_connections_current{user="hello"} 803
telemt_user_octets_from_client{user="hello"} 7154872656 (6.66 GB)
telemt_user_octets_to_client{user="hello"} 197101111712 (183.56 GB)
telemt_user_unique_ips_current{user="hello"} 89
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 50784.2 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 316718
telemt_connections_bad_total 2878
telemt_handshake_timeouts_total 27209
telemt_upstream_connect_attempt_total 97919
telemt_upstream_connect_success_total 96445
telemt_upstream_connect_fail_total 698
telemt_upstream_connect_attempts_per_request{bucket="1"} 96439
telemt_upstream_connect_attempts_per_request{bucket="2"} 704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 698
telemt_me_keepalive_timeout_total 1370
telemt_me_reconnect_attempts_total 55487
telemt_me_reconnect_success_total 55401
telemt_me_reader_eof_total 56812
telemt_me_idle_close_by_peer_total 56811
telemt_me_route_drop_no_conn_total 137906
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 215
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 588
telemt_desync_full_logged_total 208
telemt_desync_suppressed_total 380
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 259
telemt_desync_frames_bucket_total{bucket="gt_10"} 212
telemt_pool_swap_total 3
telemt_pool_force_close_total 216
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 56892
telemt_me_writer_restored_same_endpoint_total 55376
telemt_me_writer_removed_unexpected_minus_restored_total 1516
telemt_user_connections_total{user="hello"} 243689
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 3225452536 (3.00 GB)
telemt_user_octets_to_client{user="hello"} 79144808008 (73.71 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 50783.0 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 618729
telemt_connections_bad_total 152899
telemt_handshake_timeouts_total 18902
telemt_upstream_connect_attempt_total 76756
telemt_upstream_connect_success_total 76309
telemt_upstream_connect_fail_total 214
telemt_upstream_connect_attempts_per_request{bucket="1"} 76308
telemt_upstream_connect_attempts_per_request{bucket="2"} 215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31405
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 214
telemt_me_keepalive_timeout_total 987
telemt_me_reconnect_attempts_total 36052
telemt_me_reconnect_success_total 35963
telemt_me_reader_eof_total 37900
telemt_me_idle_close_by_peer_total 37896
telemt_me_route_drop_no_conn_total 231624
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 213
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1077
telemt_desync_full_logged_total 393
telemt_desync_suppressed_total 684
telemt_desync_frames_bucket_total{bucket="1_2"} 338
telemt_desync_frames_bucket_total{bucket="3_10"} 353
telemt_desync_frames_bucket_total{bucket="gt_10"} 386
telemt_pool_swap_total 4
telemt_pool_force_close_total 201
telemt_me_writer_removed_unexpected_total 37912
telemt_me_writer_restored_same_endpoint_total 35942
telemt_me_writer_removed_unexpected_minus_restored_total 1970
telemt_user_connections_total{user="hello"} 427808
telemt_user_connections_current{user="hello"} 694
telemt_user_octets_from_client{user="hello"} 5478840452 (5.10 GB)
telemt_user_octets_to_client{user="hello"} 144170650020 (134.27 GB)
telemt_user_unique_ips_current{user="hello"} 71
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 50782.1 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 402576
telemt_connections_bad_total 27816
telemt_handshake_timeouts_total 66303
telemt_upstream_connect_attempt_total 38042
telemt_upstream_connect_success_total 37891
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 37891
telemt_upstream_connect_attempts_per_request{bucket="2"} 74
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14406
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 428
telemt_me_reconnect_attempts_total 8209
telemt_me_reconnect_success_total 8182
telemt_me_reader_eof_total 8364
telemt_me_idle_close_by_peer_total 8364
telemt_me_route_drop_no_conn_total 114231
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 209
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 228
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 134
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_pool_swap_total 14
telemt_pool_force_close_total 375
telemt_me_writer_removed_unexpected_total 8364
telemt_me_writer_restored_same_endpoint_total 8161
telemt_me_writer_removed_unexpected_minus_restored_total 203
telemt_user_connections_total{user="hello"} 286358
telemt_user_connections_current{user="hello"} 419
telemt_user_octets_from_client{user="hello"} 3478725148 (3.24 GB)
telemt_user_octets_to_client{user="hello"} 104541939552 (97.36 GB)
telemt_user_unique_ips_current{user="hello"} 55
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 50780.6 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 542226
telemt_connections_bad_total 6813
telemt_handshake_timeouts_total 132424
telemt_upstream_connect_attempt_total 72237
telemt_upstream_connect_success_total 71743
telemt_upstream_connect_fail_total 234
telemt_upstream_connect_attempts_per_request{bucket="1"} 71743
telemt_upstream_connect_attempts_per_request{bucket="2"} 234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28236
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 234
telemt_me_keepalive_timeout_total 938
telemt_me_reconnect_attempts_total 34820
telemt_me_reconnect_success_total 34785
telemt_me_reader_eof_total 36493
telemt_me_idle_close_by_peer_total 36492
telemt_me_route_drop_no_conn_total 171531
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 214
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 701
telemt_desync_full_logged_total 223
telemt_desync_suppressed_total 478
telemt_desync_frames_bucket_total{bucket="1_2"} 131
telemt_desync_frames_bucket_total{bucket="3_10"} 301
telemt_desync_frames_bucket_total{bucket="gt_10"} 269
telemt_pool_swap_total 6
telemt_pool_force_close_total 263
telemt_pool_stale_pick_total 2870
telemt_me_writer_removed_unexpected_total 36505
telemt_me_writer_restored_same_endpoint_total 34760
telemt_me_writer_removed_unexpected_minus_restored_total 1745
telemt_user_connections_total{user="hello"} 378627
telemt_user_connections_current{user="hello"} 687
telemt_user_octets_from_client{user="hello"} 4958115128 (4.62 GB)
telemt_user_octets_to_client{user="hello"} 101254440644 (94.30 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 57
```