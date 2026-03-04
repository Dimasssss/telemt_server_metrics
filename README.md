# Server Metrics 2026-03-04 09:19:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 43713.8 (12h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 573907
telemt_connections_bad_total 10475
telemt_handshake_timeouts_total 6835
telemt_upstream_connect_attempt_total 27946
telemt_upstream_connect_success_total 27824
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 27824
telemt_upstream_connect_attempts_per_request{bucket="2"} 52
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12214
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 295
telemt_me_reconnect_attempts_total 5914
telemt_me_reconnect_success_total 5875
telemt_me_reader_eof_total 6036
telemt_me_idle_close_by_peer_total 6036
telemt_me_route_drop_no_conn_total 200235
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 176
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 994
telemt_desync_full_logged_total 357
telemt_desync_suppressed_total 637
telemt_desync_frames_bucket_total{bucket="1_2"} 286
telemt_desync_frames_bucket_total{bucket="3_10"} 374
telemt_desync_frames_bucket_total{bucket="gt_10"} 334
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 6036
telemt_me_writer_restored_same_endpoint_total 5854
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 475746
telemt_user_connections_current{user="hello"} 1109
telemt_user_octets_from_client{user="hello"} 5414711312 (5.04 GB)
telemt_user_octets_to_client{user="hello"} 140400193008 (130.76 GB)
telemt_user_unique_ips_current{user="hello"} 148
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 43710.1 (12h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227981
telemt_connections_bad_total 1978
telemt_handshake_timeouts_total 24450
telemt_upstream_connect_attempt_total 90420
telemt_upstream_connect_success_total 89132
telemt_upstream_connect_fail_total 606
telemt_upstream_connect_attempts_per_request{bucket="1"} 89126
telemt_upstream_connect_attempts_per_request{bucket="2"} 612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29076
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 606
telemt_me_keepalive_timeout_total 1290
telemt_me_reconnect_attempts_total 52444
telemt_me_reconnect_success_total 52363
telemt_me_reader_eof_total 53711
telemt_me_idle_close_by_peer_total 53710
telemt_me_route_drop_no_conn_total 106968
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 188
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 510
telemt_desync_full_logged_total 179
telemt_desync_suppressed_total 331
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 231
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 2
telemt_pool_force_close_total 140
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 53791
telemt_me_writer_restored_same_endpoint_total 52338
telemt_me_writer_removed_unexpected_minus_restored_total 1453
telemt_user_connections_total{user="hello"} 173157
telemt_user_connections_current{user="hello"} 539
telemt_user_octets_from_client{user="hello"} 2017525664 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 61294638168 (57.09 GB)
telemt_user_unique_ips_current{user="hello"} 75
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 43708.9 (12h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 474926
telemt_connections_bad_total 132480
telemt_handshake_timeouts_total 14512
telemt_upstream_connect_attempt_total 62973
telemt_upstream_connect_success_total 62573
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 62572
telemt_upstream_connect_attempts_per_request{bucket="2"} 192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26292
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_keepalive_timeout_total 837
telemt_me_reconnect_attempts_total 28397
telemt_me_reconnect_success_total 28321
telemt_me_reader_eof_total 29885
telemt_me_idle_close_by_peer_total 29882
telemt_me_route_drop_no_conn_total 159172
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 184
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 711
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 445
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 4
telemt_pool_force_close_total 200
telemt_me_writer_removed_unexpected_total 29896
telemt_me_writer_restored_same_endpoint_total 28300
telemt_me_writer_removed_unexpected_minus_restored_total 1596
telemt_user_connections_total{user="hello"} 312294
telemt_user_connections_current{user="hello"} 695
telemt_user_octets_from_client{user="hello"} 3086816336 (2.87 GB)
telemt_user_octets_to_client{user="hello"} 114508134096 (106.64 GB)
telemt_user_unique_ips_current{user="hello"} 78
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 43708.3 (12h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 304218
telemt_connections_bad_total 21427
telemt_handshake_timeouts_total 48356
telemt_upstream_connect_attempt_total 32147
telemt_upstream_connect_success_total 32016
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 32016
telemt_upstream_connect_attempts_per_request{bucket="2"} 64
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 360
telemt_me_reconnect_attempts_total 6563
telemt_me_reconnect_success_total 6542
telemt_me_reader_eof_total 6667
telemt_me_idle_close_by_peer_total 6667
telemt_me_route_drop_no_conn_total 86506
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 182
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 173
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 98
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 12
telemt_pool_force_close_total 292
telemt_me_writer_removed_unexpected_total 6667
telemt_me_writer_restored_same_endpoint_total 6521
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 213713
telemt_user_connections_current{user="hello"} 457
telemt_user_octets_from_client{user="hello"} 2359105816 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 74881723604 (69.74 GB)
telemt_user_unique_ips_current{user="hello"} 67
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 43706.6 (12h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 431748
telemt_connections_bad_total 6456
telemt_handshake_timeouts_total 132127
telemt_upstream_connect_attempt_total 67713
telemt_upstream_connect_success_total 67294
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 67294
telemt_upstream_connect_attempts_per_request{bucket="2"} 197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26682
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 889
telemt_me_reconnect_attempts_total 33505
telemt_me_reconnect_success_total 33478
telemt_me_reader_eof_total 35155
telemt_me_idle_close_by_peer_total 35154
telemt_me_route_drop_no_conn_total 131071
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 184
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 358
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 239
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 173
telemt_desync_frames_bucket_total{bucket="gt_10"} 122
telemt_pool_swap_total 5
telemt_pool_force_close_total 233
telemt_pool_stale_pick_total 2778
telemt_me_writer_removed_unexpected_total 35167
telemt_me_writer_restored_same_endpoint_total 33453
telemt_me_writer_removed_unexpected_minus_restored_total 1714
telemt_user_connections_total{user="hello"} 276949
telemt_user_connections_current{user="hello"} 640
telemt_user_octets_from_client{user="hello"} 3907591088 (3.64 GB)
telemt_user_octets_to_client{user="hello"} 69221299744 (64.47 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 81
```