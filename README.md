# Server Metrics 2026-03-06 05:44:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 26597.7 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215129
telemt_connections_bad_total 16022
telemt_handshake_timeouts_total 3363
telemt_upstream_connect_attempt_total 27325
telemt_upstream_connect_success_total 27101
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 27101
telemt_upstream_connect_attempts_per_request{bucket="2"} 106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10468
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 276
telemt_me_reconnect_attempts_total 9888
telemt_me_reconnect_success_total 9850
telemt_me_reader_eof_total 10190
telemt_me_idle_close_by_peer_total 10190
telemt_me_route_drop_no_conn_total 67029
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 112
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 651
telemt_desync_full_logged_total 208
telemt_desync_suppressed_total 443
telemt_desync_frames_bucket_total{bucket="1_2"} 180
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 238
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 10191
telemt_me_writer_restored_same_endpoint_total 9844
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 186494
telemt_user_connections_current{user="hello"} 668
telemt_user_octets_from_client{user="hello"} 5316096552 (4.95 GB)
telemt_user_octets_to_client{user="hello"} 71110688744 (66.23 GB)
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 26593.2 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85604
telemt_connections_bad_total 149
telemt_handshake_timeouts_total 4305
telemt_upstream_connect_attempt_total 24291
telemt_upstream_connect_success_total 24289
telemt_upstream_connect_attempts_per_request{bucket="1"} 24289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10495
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 293
telemt_me_reconnect_attempts_total 6767
telemt_me_reconnect_success_total 6742
telemt_me_reader_eof_total 6893
telemt_me_idle_close_by_peer_total 6893
telemt_me_route_drop_no_conn_total 25033
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 115
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 301
telemt_desync_full_logged_total 98
telemt_desync_suppressed_total 203
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 108
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 8
telemt_pool_force_close_total 150
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6894
telemt_me_writer_restored_same_endpoint_total 6736
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 79554
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 784093428 (747.77 MB)
telemt_user_octets_to_client{user="hello"} 25909521820 (24.13 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 26590.6 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151033
telemt_connections_bad_total 1458
telemt_handshake_timeouts_total 3559
telemt_upstream_connect_attempt_total 27557
telemt_upstream_connect_success_total 27362
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 27362
telemt_upstream_connect_attempts_per_request{bucket="2"} 88
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10796
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 330
telemt_me_reconnect_attempts_total 9250
telemt_me_reconnect_success_total 9219
telemt_me_reader_eof_total 9612
telemt_me_idle_close_by_peer_total 9612
telemt_me_route_drop_no_conn_total 42851
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 112
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 289
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 192
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 140
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 9617
telemt_me_writer_restored_same_endpoint_total 9211
telemt_me_writer_removed_unexpected_minus_restored_total 406
telemt_user_connections_total{user="hello"} 134662
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 1238700580 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 44920937604 (41.84 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 26587.2 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115473
telemt_connections_bad_total 7445
telemt_handshake_timeouts_total 5776
telemt_upstream_connect_attempt_total 19929
telemt_upstream_connect_success_total 19861
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 19861
telemt_upstream_connect_attempts_per_request{bucket="2"} 33
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8006
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 209
telemt_me_reconnect_attempts_total 4479
telemt_me_reconnect_success_total 4451
telemt_me_reader_eof_total 4607
telemt_me_idle_close_by_peer_total 4607
telemt_me_route_drop_no_conn_total 40190
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 110
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 292
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 196
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 135
telemt_pool_swap_total 8
telemt_pool_force_close_total 169
telemt_me_writer_removed_unexpected_total 4607
telemt_me_writer_restored_same_endpoint_total 4444
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 97384
telemt_user_connections_current{user="hello"} 334
telemt_user_octets_from_client{user="hello"} 1581584204 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 37033433556 (34.49 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 26586.0 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132151
telemt_connections_bad_total 1032
telemt_handshake_timeouts_total 738
telemt_upstream_connect_attempt_total 17906
telemt_upstream_connect_success_total 17863
telemt_upstream_connect_attempts_per_request{bucket="1"} 17863
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7190
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 239
telemt_me_reconnect_attempts_total 3018
telemt_me_reconnect_success_total 3004
telemt_me_reader_eof_total 3106
telemt_me_idle_close_by_peer_total 3105
telemt_me_route_drop_no_conn_total 47068
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 115
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 253
telemt_desync_full_logged_total 105
telemt_desync_suppressed_total 148
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 132
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 8
telemt_pool_force_close_total 155
telemt_me_writer_removed_unexpected_total 3110
telemt_me_writer_restored_same_endpoint_total 2997
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 128034
telemt_user_connections_current{user="hello"} 398
telemt_user_octets_from_client{user="hello"} 23816961716 (22.18 GB)
telemt_user_octets_to_client{user="hello"} 78757167164 (73.35 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 63
```