# Server Metrics 2026-03-04 08:22:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 40330.1 (11h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 467545
telemt_connections_bad_total 7997
telemt_handshake_timeouts_total 6454
telemt_upstream_connect_attempt_total 24903
telemt_upstream_connect_success_total 24790
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 24790
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10756
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 4853
telemt_me_reconnect_success_total 4818
telemt_me_reader_eof_total 4932
telemt_me_idle_close_by_peer_total 4932
telemt_me_route_drop_no_conn_total 158093
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 160
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 882
telemt_desync_full_logged_total 323
telemt_desync_suppressed_total 559
telemt_desync_frames_bucket_total{bucket="1_2"} 259
telemt_desync_frames_bucket_total{bucket="3_10"} 326
telemt_desync_frames_bucket_total{bucket="gt_10"} 297
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 4932
telemt_me_writer_restored_same_endpoint_total 4797
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 394706
telemt_user_connections_current{user="hello"} 944
telemt_user_octets_from_client{user="hello"} 4578008612 (4.26 GB)
telemt_user_octets_to_client{user="hello"} 117667040464 (109.59 GB)
telemt_user_unique_ips_current{user="hello"} 91
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 40327.1 (11h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195296
telemt_connections_bad_total 1873
telemt_handshake_timeouts_total 23951
telemt_upstream_connect_attempt_total 82576
telemt_upstream_connect_success_total 81346
telemt_upstream_connect_fail_total 577
telemt_upstream_connect_attempts_per_request{bucket="1"} 81340
telemt_upstream_connect_attempts_per_request{bucket="2"} 583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26236
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 577
telemt_me_keepalive_timeout_total 1233
telemt_me_reconnect_attempts_total 47906
telemt_me_reconnect_success_total 47828
telemt_me_reader_eof_total 49026
telemt_me_idle_close_by_peer_total 49025
telemt_me_route_drop_no_conn_total 83440
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 173
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 428
telemt_desync_full_logged_total 152
telemt_desync_suppressed_total 276
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 198
telemt_desync_frames_bucket_total{bucket="gt_10"} 141
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 49106
telemt_me_writer_restored_same_endpoint_total 47803
telemt_me_writer_removed_unexpected_minus_restored_total 1303
telemt_user_connections_total{user="hello"} 142006
telemt_user_connections_current{user="hello"} 405
telemt_user_octets_from_client{user="hello"} 1687436920 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 53896807792 (50.20 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 40325.9 (11h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 399655
telemt_connections_bad_total 115312
telemt_handshake_timeouts_total 11259
telemt_upstream_connect_attempt_total 60278
telemt_upstream_connect_success_total 59918
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 59917
telemt_upstream_connect_attempts_per_request{bucket="2"} 172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25496
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_timeout_total 802
telemt_me_reconnect_attempts_total 27738
telemt_me_reconnect_success_total 27667
telemt_me_reader_eof_total 29213
telemt_me_idle_close_by_peer_total 29210
telemt_me_route_drop_no_conn_total 131766
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 170
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 616
telemt_desync_full_logged_total 233
telemt_desync_suppressed_total 383
telemt_desync_frames_bucket_total{bucket="1_2"} 173
telemt_desync_frames_bucket_total{bucket="3_10"} 222
telemt_desync_frames_bucket_total{bucket="gt_10"} 221
telemt_pool_swap_total 4
telemt_pool_force_close_total 199
telemt_me_writer_removed_unexpected_total 29224
telemt_me_writer_restored_same_endpoint_total 27646
telemt_me_writer_removed_unexpected_minus_restored_total 1578
telemt_user_connections_total{user="hello"} 258145
telemt_user_connections_current{user="hello"} 498
telemt_user_octets_from_client{user="hello"} 2512067632 (2.34 GB)
telemt_user_octets_to_client{user="hello"} 97892561200 (91.17 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 40324.7 (11h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224445
telemt_connections_bad_total 18387
telemt_handshake_timeouts_total 8126
telemt_upstream_connect_attempt_total 30250
telemt_upstream_connect_success_total 30123
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 30123
telemt_upstream_connect_attempts_per_request{bucket="2"} 62
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11427
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 347
telemt_me_reconnect_attempts_total 6332
telemt_me_reconnect_success_total 6316
telemt_me_reader_eof_total 6435
telemt_me_idle_close_by_peer_total 6435
telemt_me_route_drop_no_conn_total 73219
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 167
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 11
telemt_pool_force_close_total 261
telemt_me_writer_removed_unexpected_total 6435
telemt_me_writer_restored_same_endpoint_total 6295
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 178781
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 1951614088 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 63205282344 (58.86 GB)
telemt_user_unique_ips_current{user="hello"} 37
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 40323.5 (11h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 376072
telemt_connections_bad_total 6444
telemt_handshake_timeouts_total 131862
telemt_upstream_connect_attempt_total 59685
telemt_upstream_connect_success_total 59286
telemt_upstream_connect_fail_total 187
telemt_upstream_connect_attempts_per_request{bucket="1"} 59286
telemt_upstream_connect_attempts_per_request{bucket="2"} 187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35506
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23624
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 187
telemt_me_keepalive_timeout_total 799
telemt_me_reconnect_attempts_total 28352
telemt_me_reconnect_success_total 28329
telemt_me_reader_eof_total 29782
telemt_me_idle_close_by_peer_total 29781
telemt_me_route_drop_no_conn_total 107281
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 171
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 250
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 165
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 122
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 4
telemt_pool_force_close_total 117
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 29796
telemt_me_writer_restored_same_endpoint_total 28304
telemt_me_writer_removed_unexpected_minus_restored_total 1492
telemt_user_connections_total{user="hello"} 229033
telemt_user_connections_current{user="hello"} 557
telemt_user_octets_from_client{user="hello"} 3088277228 (2.88 GB)
telemt_user_octets_to_client{user="hello"} 58212019584 (54.21 GB)
telemt_user_unique_ips_current{user="hello"} 56
```