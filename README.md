# Server Metrics 2026-03-04 09:14:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 43406.7 (12h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 562392
telemt_connections_bad_total 10448
telemt_handshake_timeouts_total 6755
telemt_upstream_connect_attempt_total 27581
telemt_upstream_connect_success_total 27460
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 27460
telemt_upstream_connect_attempts_per_request{bucket="2"} 52
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12031
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 292
telemt_me_reconnect_attempts_total 5760
telemt_me_reconnect_success_total 5721
telemt_me_reader_eof_total 5875
telemt_me_idle_close_by_peer_total 5875
telemt_me_route_drop_no_conn_total 195409
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 176
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 980
telemt_desync_full_logged_total 354
telemt_desync_suppressed_total 626
telemt_desync_frames_bucket_total{bucket="1_2"} 285
telemt_desync_frames_bucket_total{bucket="3_10"} 369
telemt_desync_frames_bucket_total{bucket="gt_10"} 326
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 5875
telemt_me_writer_restored_same_endpoint_total 5700
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 467759
telemt_user_connections_current{user="hello"} 1024
telemt_user_octets_from_client{user="hello"} 5372716500 (5.00 GB)
telemt_user_octets_to_client{user="hello"} 138244280904 (128.75 GB)
telemt_user_unique_ips_current{user="hello"} 105
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 43403.2 (12h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224762
telemt_connections_bad_total 1978
telemt_handshake_timeouts_total 24418
telemt_upstream_connect_attempt_total 89734
telemt_upstream_connect_success_total 88458
telemt_upstream_connect_fail_total 599
telemt_upstream_connect_attempts_per_request{bucket="1"} 88452
telemt_upstream_connect_attempts_per_request{bucket="2"} 605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28804
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 599
telemt_me_keepalive_timeout_total 1282
telemt_me_reconnect_attempts_total 52067
telemt_me_reconnect_success_total 51986
telemt_me_reader_eof_total 53318
telemt_me_idle_close_by_peer_total 53317
telemt_me_route_drop_no_conn_total 105175
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 186
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 509
telemt_desync_full_logged_total 178
telemt_desync_suppressed_total 331
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 231
telemt_desync_frames_bucket_total{bucket="gt_10"} 177
telemt_pool_swap_total 2
telemt_pool_force_close_total 140
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 53398
telemt_me_writer_restored_same_endpoint_total 51961
telemt_me_writer_removed_unexpected_minus_restored_total 1437
telemt_user_connections_total{user="hello"} 170042
telemt_user_connections_current{user="hello"} 450
telemt_user_octets_from_client{user="hello"} 1997600368 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 60467522480 (56.31 GB)
telemt_user_unique_ips_current{user="hello"} 40
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 43401.9 (12h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 467323
telemt_connections_bad_total 130490
telemt_handshake_timeouts_total 14270
telemt_upstream_connect_attempt_total 62651
telemt_upstream_connect_success_total 62253
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 62252
telemt_upstream_connect_attempts_per_request{bucket="2"} 190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_keepalive_timeout_total 836
telemt_me_reconnect_attempts_total 28282
telemt_me_reconnect_success_total 28207
telemt_me_reader_eof_total 29766
telemt_me_idle_close_by_peer_total 29763
telemt_me_route_drop_no_conn_total 156381
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 183
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 703
telemt_desync_full_logged_total 263
telemt_desync_suppressed_total 440
telemt_desync_frames_bucket_total{bucket="1_2"} 203
telemt_desync_frames_bucket_total{bucket="3_10"} 244
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 4
telemt_pool_force_close_total 200
telemt_me_writer_removed_unexpected_total 29777
telemt_me_writer_restored_same_endpoint_total 28186
telemt_me_writer_removed_unexpected_minus_restored_total 1591
telemt_user_connections_total{user="hello"} 306973
telemt_user_connections_current{user="hello"} 719
telemt_user_octets_from_client{user="hello"} 3029862284 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 113593064052 (105.79 GB)
telemt_user_unique_ips_current{user="hello"} 66
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 43400.8 (12h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 295576
telemt_connections_bad_total 21152
telemt_handshake_timeouts_total 42221
telemt_upstream_connect_attempt_total 31957
telemt_upstream_connect_success_total 31826
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 31826
telemt_upstream_connect_attempts_per_request{bucket="2"} 64
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12039
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 358
telemt_me_reconnect_attempts_total 6549
telemt_me_reconnect_success_total 6528
telemt_me_reader_eof_total 6653
telemt_me_idle_close_by_peer_total 6653
telemt_me_route_drop_no_conn_total 85251
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 181
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 173
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 98
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 12
telemt_pool_force_close_total 292
telemt_me_writer_removed_unexpected_total 6653
telemt_me_writer_restored_same_endpoint_total 6507
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 210575
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 2335131864 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 73813343208 (68.74 GB)
telemt_user_unique_ips_current{user="hello"} 40
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 43399.6 (12h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 426803
telemt_connections_bad_total 6454
telemt_handshake_timeouts_total 132091
telemt_upstream_connect_attempt_total 67692
telemt_upstream_connect_success_total 67273
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 67273
telemt_upstream_connect_attempts_per_request{bucket="2"} 197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26665
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 879
telemt_me_reconnect_attempts_total 33505
telemt_me_reconnect_success_total 33478
telemt_me_reader_eof_total 35155
telemt_me_idle_close_by_peer_total 35154
telemt_me_route_drop_no_conn_total 129512
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 184
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 341
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 226
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 165
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 5
telemt_pool_force_close_total 118
telemt_pool_stale_pick_total 2758
telemt_me_writer_removed_unexpected_total 35167
telemt_me_writer_restored_same_endpoint_total 33453
telemt_me_writer_removed_unexpected_minus_restored_total 1714
telemt_user_connections_total{user="hello"} 272356
telemt_user_connections_current{user="hello"} 630
telemt_user_octets_from_client{user="hello"} 3889479448 (3.62 GB)
telemt_user_octets_to_client{user="hello"} 68396320560 (63.70 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 71
```