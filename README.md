# Server Metrics 2026-03-06 06:36:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 29669.0 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 267512
telemt_connections_bad_total 16101
telemt_handshake_timeouts_total 3740
telemt_upstream_connect_attempt_total 29559
telemt_upstream_connect_success_total 29300
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 29300
telemt_upstream_connect_attempts_per_request{bucket="2"} 117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11157
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 302
telemt_me_reconnect_attempts_total 10355
telemt_me_reconnect_success_total 10315
telemt_me_reader_eof_total 10664
telemt_me_idle_close_by_peer_total 10664
telemt_me_route_drop_no_conn_total 92489
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 123
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 882
telemt_desync_full_logged_total 268
telemt_desync_suppressed_total 614
telemt_desync_frames_bucket_total{bucket="1_2"} 232
telemt_desync_frames_bucket_total{bucket="3_10"} 309
telemt_desync_frames_bucket_total{bucket="gt_10"} 341
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 10666
telemt_me_writer_restored_same_endpoint_total 10309
telemt_me_writer_removed_unexpected_minus_restored_total 357
telemt_user_connections_total{user="hello"} 236246
telemt_user_connections_current{user="hello"} 879
telemt_user_octets_from_client{user="hello"} 8465949480 (7.88 GB)
telemt_user_octets_to_client{user="hello"} 86021981020 (80.11 GB)
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 29664.4 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112792
telemt_connections_bad_total 154
telemt_handshake_timeouts_total 10812
telemt_upstream_connect_attempt_total 25041
telemt_upstream_connect_success_total 25039
telemt_upstream_connect_attempts_per_request{bucket="1"} 25039
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14120
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10911
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 300
telemt_me_reconnect_attempts_total 6777
telemt_me_reconnect_success_total 6750
telemt_me_reader_eof_total 6901
telemt_me_idle_close_by_peer_total 6901
telemt_me_route_drop_no_conn_total 32389
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 125
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 365
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 247
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 132
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 10
telemt_pool_force_close_total 197
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6902
telemt_me_writer_restored_same_endpoint_total 6743
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 99833
telemt_user_connections_current{user="hello"} 292
telemt_user_octets_from_client{user="hello"} 1109309580 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 33165315252 (30.89 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 29661.8 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191467
telemt_connections_bad_total 1758
telemt_handshake_timeouts_total 4744
telemt_upstream_connect_attempt_total 33759
telemt_upstream_connect_success_total 33519
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 33519
telemt_upstream_connect_attempts_per_request{bucket="2"} 109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13510
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 467
telemt_me_reconnect_attempts_total 12535
telemt_me_reconnect_success_total 12495
telemt_me_reader_eof_total 13067
telemt_me_idle_close_by_peer_total 13066
telemt_me_route_drop_no_conn_total 57302
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 123
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 362
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 243
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 125
telemt_desync_frames_bucket_total{bucket="gt_10"} 163
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 13093
telemt_me_writer_restored_same_endpoint_total 12473
telemt_me_writer_restored_fallback_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 606
telemt_user_connections_total{user="hello"} 169889
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 1725359840 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 55634983100 (51.81 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 29658.4 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153021
telemt_connections_bad_total 14363
telemt_handshake_timeouts_total 6430
telemt_upstream_connect_attempt_total 21508
telemt_upstream_connect_success_total 21435
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 21435
telemt_upstream_connect_attempts_per_request{bucket="2"} 35
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8621
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 228
telemt_me_reconnect_attempts_total 4868
telemt_me_reconnect_success_total 4836
telemt_me_reader_eof_total 5007
telemt_me_idle_close_by_peer_total 5007
telemt_me_route_drop_no_conn_total 50572
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 119
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 357
telemt_desync_full_logged_total 113
telemt_desync_suppressed_total 244
telemt_desync_frames_bucket_total{bucket="1_2"} 70
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 157
telemt_pool_swap_total 9
telemt_pool_force_close_total 214
telemt_me_writer_removed_unexpected_total 5008
telemt_me_writer_restored_same_endpoint_total 4829
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 126079
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 1878486704 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 43142748244 (40.18 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 29657.4 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166062
telemt_connections_bad_total 3276
telemt_handshake_timeouts_total 959
telemt_upstream_connect_attempt_total 20549
telemt_upstream_connect_success_total 20502
telemt_upstream_connect_attempts_per_request{bucket="1"} 20502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8264
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 317
telemt_me_reconnect_attempts_total 3701
telemt_me_reconnect_success_total 3685
telemt_me_reader_eof_total 3803
telemt_me_idle_close_by_peer_total 3802
telemt_me_route_drop_no_conn_total 62691
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 126
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 361
telemt_desync_full_logged_total 149
telemt_desync_suppressed_total 212
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 173
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_pool_swap_total 9
telemt_pool_force_close_total 196
telemt_pool_stale_pick_total 4
telemt_me_writer_removed_unexpected_total 3818
telemt_me_writer_restored_same_endpoint_total 3678
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 158712
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 24170989900 (22.51 GB)
telemt_user_octets_to_client{user="hello"} 98010133912 (91.28 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 60
```