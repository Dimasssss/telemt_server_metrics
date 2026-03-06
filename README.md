# Server Metrics 2026-03-06 07:27:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 32741.0 (9h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 330323
telemt_connections_bad_total 16209
telemt_handshake_timeouts_total 3929
telemt_upstream_connect_attempt_total 33263
telemt_upstream_connect_success_total 32921
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 32921
telemt_upstream_connect_attempts_per_request{bucket="2"} 153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12545
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 60
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_keepalive_timeout_total 341
telemt_me_reconnect_attempts_total 11714
telemt_me_reconnect_success_total 11666
telemt_me_reader_eof_total 12069
telemt_me_idle_close_by_peer_total 12069
telemt_me_route_drop_no_conn_total 115381
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 137
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1114
telemt_desync_full_logged_total 346
telemt_desync_suppressed_total 768
telemt_desync_frames_bucket_total{bucket="1_2"} 304
telemt_desync_frames_bucket_total{bucket="3_10"} 361
telemt_desync_frames_bucket_total{bucket="gt_10"} 449
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 12072
telemt_me_writer_restored_same_endpoint_total 11660
telemt_me_writer_removed_unexpected_minus_restored_total 412
telemt_user_connections_total{user="hello"} 291117
telemt_user_connections_current{user="hello"} 894
telemt_user_octets_from_client{user="hello"} 9774997340 (9.10 GB)
telemt_user_octets_to_client{user="hello"} 104917778496 (97.71 GB)
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 32736.3 (9h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142742
telemt_connections_bad_total 182
telemt_handshake_timeouts_total 15973
telemt_upstream_connect_attempt_total 26173
telemt_upstream_connect_success_total 26171
telemt_upstream_connect_attempts_per_request{bucket="1"} 26171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 318
telemt_me_reconnect_attempts_total 6795
telemt_me_reconnect_success_total 6765
telemt_me_reader_eof_total 6916
telemt_me_idle_close_by_peer_total 6916
telemt_me_route_drop_no_conn_total 42015
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 141
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 433
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 290
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 161
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 11
telemt_pool_force_close_total 238
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6917
telemt_me_writer_restored_same_endpoint_total 6758
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 124019
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 1422732948 (1.33 GB)
telemt_user_octets_to_client{user="hello"} 39806435192 (37.07 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 32733.7 (9h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 251403
telemt_connections_bad_total 1806
telemt_handshake_timeouts_total 8073
telemt_upstream_connect_attempt_total 36753
telemt_upstream_connect_success_total 36470
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 36470
telemt_upstream_connect_attempts_per_request{bucket="2"} 128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14779
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 518
telemt_me_reconnect_attempts_total 14114
telemt_me_reconnect_success_total 14073
telemt_me_reader_eof_total 14726
telemt_me_idle_close_by_peer_total 14724
telemt_me_route_drop_no_conn_total 74131
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 134
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 593
telemt_desync_full_logged_total 181
telemt_desync_suppressed_total 412
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 213
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 5
telemt_pool_force_close_total 173
telemt_pool_stale_pick_total 227
telemt_me_writer_removed_unexpected_total 14754
telemt_me_writer_restored_same_endpoint_total 14051
telemt_me_writer_restored_fallback_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 689
telemt_user_connections_total{user="hello"} 220408
telemt_user_connections_current{user="hello"} 573
telemt_user_octets_from_client{user="hello"} 2279121144 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 68490914688 (63.79 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 32730.3 (9h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190261
telemt_connections_bad_total 24199
telemt_handshake_timeouts_total 7800
telemt_upstream_connect_attempt_total 22962
telemt_upstream_connect_success_total 22883
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 22883
telemt_upstream_connect_attempts_per_request{bucket="2"} 38
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9091
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 250
telemt_me_reconnect_attempts_total 5020
telemt_me_reconnect_success_total 4987
telemt_me_reader_eof_total 5159
telemt_me_idle_close_by_peer_total 5159
telemt_me_route_drop_no_conn_total 59358
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 132
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 443
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 300
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 166
telemt_desync_frames_bucket_total{bucket="gt_10"} 193
telemt_pool_swap_total 11
telemt_pool_force_close_total 267
telemt_me_writer_removed_unexpected_total 5160
telemt_me_writer_restored_same_endpoint_total 4980
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 151241
telemt_user_connections_current{user="hello"} 307
telemt_user_octets_from_client{user="hello"} 2115246984 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 53211919248 (49.56 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 32729.2 (9h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203072
telemt_connections_bad_total 3295
telemt_handshake_timeouts_total 1153
telemt_upstream_connect_attempt_total 21811
telemt_upstream_connect_success_total 21761
telemt_upstream_connect_attempts_per_request{bucket="1"} 21761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12840
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8818
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 332
telemt_me_reconnect_attempts_total 3789
telemt_me_reconnect_success_total 3770
telemt_me_reader_eof_total 3892
telemt_me_idle_close_by_peer_total 3891
telemt_me_route_drop_no_conn_total 82297
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 141
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 455
telemt_desync_full_logged_total 179
telemt_desync_suppressed_total 276
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 208
telemt_desync_frames_bucket_total{bucket="gt_10"} 162
telemt_pool_swap_total 10
telemt_pool_force_close_total 208
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 3907
telemt_me_writer_restored_same_endpoint_total 3763
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 194688
telemt_user_connections_current{user="hello"} 612
telemt_user_octets_from_client{user="hello"} 24571990720 (22.88 GB)
telemt_user_octets_to_client{user="hello"} 116463530640 (108.47 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 90
```