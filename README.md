# Server Metrics 2026-03-06 07:47:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 33972.4 (9h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 355134
telemt_connections_bad_total 16320
telemt_handshake_timeouts_total 3996
telemt_upstream_connect_attempt_total 35405
telemt_upstream_connect_success_total 35054
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 35054
telemt_upstream_connect_attempts_per_request{bucket="2"} 158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13392
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 68
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 368
telemt_me_reconnect_attempts_total 12820
telemt_me_reconnect_success_total 12770
telemt_me_reader_eof_total 13219
telemt_me_idle_close_by_peer_total 13219
telemt_me_route_drop_no_conn_total 124902
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 141
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1157
telemt_desync_full_logged_total 362
telemt_desync_suppressed_total 795
telemt_desync_frames_bucket_total{bucket="1_2"} 319
telemt_desync_frames_bucket_total{bucket="3_10"} 381
telemt_desync_frames_bucket_total{bucket="gt_10"} 457
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 13222
telemt_me_writer_restored_same_endpoint_total 12764
telemt_me_writer_removed_unexpected_minus_restored_total 458
telemt_user_connections_total{user="hello"} 314633
telemt_user_connections_current{user="hello"} 844
telemt_user_octets_from_client{user="hello"} 10207021856 (9.51 GB)
telemt_user_octets_to_client{user="hello"} 113886336080 (106.06 GB)
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 33967.8 (9h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156165
telemt_connections_bad_total 183
telemt_handshake_timeouts_total 18195
telemt_upstream_connect_attempt_total 26668
telemt_upstream_connect_success_total 26666
telemt_upstream_connect_attempts_per_request{bucket="1"} 26666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11746
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 6804
telemt_me_reconnect_success_total 6773
telemt_me_reader_eof_total 6925
telemt_me_idle_close_by_peer_total 6925
telemt_me_route_drop_no_conn_total 45870
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 145
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 460
telemt_desync_full_logged_total 153
telemt_desync_suppressed_total 307
telemt_desync_frames_bucket_total{bucket="1_2"} 131
telemt_desync_frames_bucket_total{bucket="3_10"} 174
telemt_desync_frames_bucket_total{bucket="gt_10"} 155
telemt_pool_swap_total 11
telemt_pool_force_close_total 238
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6926
telemt_me_writer_restored_same_endpoint_total 6766
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 135058
telemt_user_connections_current{user="hello"} 432
telemt_user_octets_from_client{user="hello"} 1531814556 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 42736574032 (39.80 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 33965.2 (9h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 273304
telemt_connections_bad_total 1985
telemt_handshake_timeouts_total 9585
telemt_upstream_connect_attempt_total 37438
telemt_upstream_connect_success_total 37148
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 37148
telemt_upstream_connect_attempts_per_request{bucket="2"} 131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15065
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 532
telemt_me_reconnect_attempts_total 14181
telemt_me_reconnect_success_total 14139
telemt_me_reader_eof_total 14792
telemt_me_idle_close_by_peer_total 14790
telemt_me_route_drop_no_conn_total 81389
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 138
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 709
telemt_desync_full_logged_total 214
telemt_desync_suppressed_total 495
telemt_desync_frames_bucket_total{bucket="1_2"} 138
telemt_desync_frames_bucket_total{bucket="3_10"} 253
telemt_desync_frames_bucket_total{bucket="gt_10"} 318
telemt_pool_swap_total 5
telemt_pool_force_close_total 173
telemt_pool_stale_pick_total 227
telemt_me_writer_removed_unexpected_total 14821
telemt_me_writer_restored_same_endpoint_total 14117
telemt_me_writer_restored_fallback_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 690
telemt_user_connections_total{user="hello"} 238225
telemt_user_connections_current{user="hello"} 538
telemt_user_octets_from_client{user="hello"} 2460477000 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 74262529320 (69.16 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 33961.9 (9h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206076
telemt_connections_bad_total 28165
telemt_handshake_timeouts_total 8895
telemt_upstream_connect_attempt_total 23456
telemt_upstream_connect_success_total 23369
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 23369
telemt_upstream_connect_attempts_per_request{bucket="2"} 42
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9282
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 257
telemt_me_reconnect_attempts_total 5038
telemt_me_reconnect_success_total 5004
telemt_me_reader_eof_total 5176
telemt_me_idle_close_by_peer_total 5176
telemt_me_route_drop_no_conn_total 62738
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 136
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 492
telemt_desync_full_logged_total 165
telemt_desync_suppressed_total 327
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 185
telemt_desync_frames_bucket_total{bucket="gt_10"} 215
telemt_pool_swap_total 11
telemt_pool_force_close_total 267
telemt_me_writer_removed_unexpected_total 5177
telemt_me_writer_restored_same_endpoint_total 4997
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 161510
telemt_user_connections_current{user="hello"} 324
telemt_user_octets_from_client{user="hello"} 2242313356 (2.09 GB)
telemt_user_octets_to_client{user="hello"} 54695407748 (50.94 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 33961.0 (9h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218878
telemt_connections_bad_total 3301
telemt_handshake_timeouts_total 1209
telemt_upstream_connect_attempt_total 22731
telemt_upstream_connect_success_total 22676
telemt_upstream_connect_attempts_per_request{bucket="1"} 22676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9163
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 346
telemt_me_reconnect_attempts_total 4013
telemt_me_reconnect_success_total 3993
telemt_me_reader_eof_total 4122
telemt_me_idle_close_by_peer_total 4121
telemt_me_route_drop_no_conn_total 90010
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 145
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 467
telemt_desync_full_logged_total 185
telemt_desync_suppressed_total 282
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 210
telemt_desync_frames_bucket_total{bucket="gt_10"} 162
telemt_pool_swap_total 10
telemt_pool_force_close_total 208
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 4137
telemt_me_writer_restored_same_endpoint_total 3986
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 209752
telemt_user_connections_current{user="hello"} 509
telemt_user_octets_from_client{user="hello"} 24762593116 (23.06 GB)
telemt_user_octets_to_client{user="hello"} 123734819864 (115.24 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 94
```