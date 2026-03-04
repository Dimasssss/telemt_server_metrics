# Server Metrics 2026-03-04 08:48:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 41870.9 (11h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 502308
telemt_connections_bad_total 8061
telemt_handshake_timeouts_total 6618
telemt_upstream_connect_attempt_total 26059
telemt_upstream_connect_success_total 25945
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 25945
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11320
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 271
telemt_me_reconnect_attempts_total 5218
telemt_me_reconnect_success_total 5181
telemt_me_reader_eof_total 5313
telemt_me_idle_close_by_peer_total 5313
telemt_me_route_drop_no_conn_total 172025
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 168
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 911
telemt_desync_full_logged_total 333
telemt_desync_suppressed_total 578
telemt_desync_frames_bucket_total{bucket="1_2"} 266
telemt_desync_frames_bucket_total{bucket="3_10"} 340
telemt_desync_frames_bucket_total{bucket="gt_10"} 305
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 5313
telemt_me_writer_restored_same_endpoint_total 5160
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 426465
telemt_user_connections_current{user="hello"} 940
telemt_user_octets_from_client{user="hello"} 5009622204 (4.67 GB)
telemt_user_octets_to_client{user="hello"} 128109954444 (119.31 GB)
telemt_user_unique_ips_current{user="hello"} 88
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 41867.4 (11h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208283
telemt_connections_bad_total 1927
telemt_handshake_timeouts_total 24225
telemt_upstream_connect_attempt_total 86473
telemt_upstream_connect_success_total 85219
telemt_upstream_connect_fail_total 589
telemt_upstream_connect_attempts_per_request{bucket="1"} 85213
telemt_upstream_connect_attempts_per_request{bucket="2"} 595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27570
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 589
telemt_me_keepalive_timeout_total 1258
telemt_me_reconnect_attempts_total 50288
telemt_me_reconnect_success_total 50208
telemt_me_reader_eof_total 51491
telemt_me_idle_close_by_peer_total 51490
telemt_me_route_drop_no_conn_total 93898
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
telemt_me_writer_removed_unexpected_total 51571
telemt_me_writer_restored_same_endpoint_total 50183
telemt_me_writer_removed_unexpected_minus_restored_total 1388
telemt_user_connections_total{user="hello"} 154369
telemt_user_connections_current{user="hello"} 395
telemt_user_octets_from_client{user="hello"} 1904662084 (1.77 GB)
telemt_user_octets_to_client{user="hello"} 56722739912 (52.83 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 41866.3 (11h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 429540
telemt_connections_bad_total 123497
telemt_handshake_timeouts_total 12420
telemt_upstream_connect_attempt_total 61318
telemt_upstream_connect_success_total 60938
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 60937
telemt_upstream_connect_attempts_per_request{bucket="2"} 182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25803
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_keepalive_timeout_total 818
telemt_me_reconnect_attempts_total 27949
telemt_me_reconnect_success_total 27876
telemt_me_reader_eof_total 29430
telemt_me_idle_close_by_peer_total 29427
telemt_me_route_drop_no_conn_total 142096
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 177
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 652
telemt_desync_full_logged_total 246
telemt_desync_suppressed_total 406
telemt_desync_frames_bucket_total{bucket="1_2"} 189
telemt_desync_frames_bucket_total{bucket="3_10"} 231
telemt_desync_frames_bucket_total{bucket="gt_10"} 232
telemt_pool_swap_total 4
telemt_pool_force_close_total 199
telemt_me_writer_removed_unexpected_total 29441
telemt_me_writer_restored_same_endpoint_total 27855
telemt_me_writer_removed_unexpected_minus_restored_total 1586
telemt_user_connections_total{user="hello"} 278410
telemt_user_connections_current{user="hello"} 530
telemt_user_octets_from_client{user="hello"} 2739785608 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 104838548976 (97.64 GB)
telemt_user_unique_ips_current{user="hello"} 57
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 41865.1 (11h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 247716
telemt_connections_bad_total 19784
telemt_handshake_timeouts_total 14557
telemt_upstream_connect_attempt_total 31348
telemt_upstream_connect_success_total 31219
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 31219
telemt_upstream_connect_attempts_per_request{bucket="2"} 63
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11816
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 356
telemt_me_reconnect_attempts_total 6528
telemt_me_reconnect_success_total 6509
telemt_me_reader_eof_total 6634
telemt_me_idle_close_by_peer_total 6634
telemt_me_route_drop_no_conn_total 78569
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
telemt_user_connections_total{user="hello"} 193228
telemt_user_connections_current{user="hello"} 389
telemt_user_octets_from_client{user="hello"} 2177005404 (2.03 GB)
telemt_user_octets_to_client{user="hello"} 67996014632 (63.33 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 41863.9 (11h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 401660
telemt_connections_bad_total 6449
telemt_handshake_timeouts_total 132042
telemt_upstream_connect_attempt_total 63944
telemt_upstream_connect_success_total 63531
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 63531
telemt_upstream_connect_attempts_per_request{bucket="2"} 194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25185
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_keepalive_timeout_total 840
telemt_me_reconnect_attempts_total 31142
telemt_me_reconnect_success_total 31119
telemt_me_reader_eof_total 32689
telemt_me_idle_close_by_peer_total 32688
telemt_me_route_drop_no_conn_total 116692
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 179
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 267
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 175
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 131
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 4
telemt_pool_force_close_total 117
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 32702
telemt_me_writer_restored_same_endpoint_total 31094
telemt_me_writer_removed_unexpected_minus_restored_total 1608
telemt_user_connections_total{user="hello"} 249275
telemt_user_connections_current{user="hello"} 458
telemt_user_octets_from_client{user="hello"} 3675509604 (3.42 GB)
telemt_user_octets_to_client{user="hello"} 62091431712 (57.83 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 43
```