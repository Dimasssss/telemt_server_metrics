# Server Metrics 2026-03-06 07:57:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 34587.0 (9h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 367851
telemt_connections_bad_total 17020
telemt_handshake_timeouts_total 4081
telemt_upstream_connect_attempt_total 36056
telemt_upstream_connect_success_total 35702
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 35702
telemt_upstream_connect_attempts_per_request{bucket="2"} 159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13676
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 70
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_keepalive_timeout_total 378
telemt_me_reconnect_attempts_total 13071
telemt_me_reconnect_success_total 13021
telemt_me_reader_eof_total 13475
telemt_me_idle_close_by_peer_total 13475
telemt_me_route_drop_no_conn_total 129816
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 143
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1216
telemt_desync_full_logged_total 383
telemt_desync_suppressed_total 833
telemt_desync_frames_bucket_total{bucket="1_2"} 342
telemt_desync_frames_bucket_total{bucket="3_10"} 404
telemt_desync_frames_bucket_total{bucket="gt_10"} 470
telemt_pool_swap_total 5
telemt_pool_force_close_total 281
telemt_me_writer_removed_unexpected_total 13478
telemt_me_writer_restored_same_endpoint_total 13013
telemt_me_writer_removed_unexpected_minus_restored_total 465
telemt_user_connections_total{user="hello"} 326035
telemt_user_connections_current{user="hello"} 841
telemt_user_octets_from_client{user="hello"} 10377476304 (9.66 GB)
telemt_user_octets_to_client{user="hello"} 116955082324 (108.92 GB)
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 34582.3 (9h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 162269
telemt_connections_bad_total 290
telemt_handshake_timeouts_total 18234
telemt_upstream_connect_attempt_total 27032
telemt_upstream_connect_success_total 27029
telemt_upstream_connect_attempts_per_request{bucket="1"} 27029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11936
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 322
telemt_me_reconnect_attempts_total 6819
telemt_me_reconnect_success_total 6788
telemt_me_reader_eof_total 6940
telemt_me_idle_close_by_peer_total 6940
telemt_me_route_drop_no_conn_total 47432
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 149
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 481
telemt_desync_full_logged_total 158
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 138
telemt_desync_frames_bucket_total{bucket="3_10"} 180
telemt_desync_frames_bucket_total{bucket="gt_10"} 163
telemt_pool_swap_total 11
telemt_pool_force_close_total 238
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6941
telemt_me_writer_restored_same_endpoint_total 6781
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 140772
telemt_user_connections_current{user="hello"} 408
telemt_user_octets_from_client{user="hello"} 1654961720 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 44308996796 (41.27 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 34579.7 (9h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 284481
telemt_connections_bad_total 2041
telemt_handshake_timeouts_total 10265
telemt_upstream_connect_attempt_total 37821
telemt_upstream_connect_success_total 37531
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 37531
telemt_upstream_connect_attempts_per_request{bucket="2"} 131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15251
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 542
telemt_me_reconnect_attempts_total 14219
telemt_me_reconnect_success_total 14176
telemt_me_reader_eof_total 14829
telemt_me_idle_close_by_peer_total 14827
telemt_me_route_drop_no_conn_total 84424
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 142
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 785
telemt_desync_full_logged_total 237
telemt_desync_suppressed_total 548
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 287
telemt_desync_frames_bucket_total{bucket="gt_10"} 345
telemt_pool_swap_total 5
telemt_pool_force_close_total 173
telemt_pool_stale_pick_total 227
telemt_me_writer_removed_unexpected_total 14858
telemt_me_writer_restored_same_endpoint_total 14154
telemt_me_writer_restored_fallback_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 690
telemt_user_connections_total{user="hello"} 246723
telemt_user_connections_current{user="hello"} 573
telemt_user_octets_from_client{user="hello"} 2859852388 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 77952454436 (72.60 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 34576.4 (9h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214057
telemt_connections_bad_total 30130
telemt_handshake_timeouts_total 9883
telemt_upstream_connect_attempt_total 23727
telemt_upstream_connect_success_total 23640
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 23640
telemt_upstream_connect_attempts_per_request{bucket="2"} 42
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9386
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 261
telemt_me_reconnect_attempts_total 5046
telemt_me_reconnect_success_total 5011
telemt_me_reader_eof_total 5183
telemt_me_idle_close_by_peer_total 5183
telemt_me_route_drop_no_conn_total 64458
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 139
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 522
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 348
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 193
telemt_desync_frames_bucket_total{bucket="gt_10"} 232
telemt_pool_swap_total 12
telemt_pool_force_close_total 286
telemt_me_writer_removed_unexpected_total 5184
telemt_me_writer_restored_same_endpoint_total 5004
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 166352
telemt_user_connections_current{user="hello"} 318
telemt_user_octets_from_client{user="hello"} 2285701332 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 55845491244 (52.01 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 34575.4 (9h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225547
telemt_connections_bad_total 3311
telemt_handshake_timeouts_total 1218
telemt_upstream_connect_attempt_total 23362
telemt_upstream_connect_success_total 23307
telemt_upstream_connect_attempts_per_request{bucket="1"} 23307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9439
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 359
telemt_me_reconnect_attempts_total 4234
telemt_me_reconnect_success_total 4213
telemt_me_reader_eof_total 4353
telemt_me_idle_close_by_peer_total 4352
telemt_me_route_drop_no_conn_total 93096
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 149
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 493
telemt_desync_full_logged_total 192
telemt_desync_suppressed_total 301
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 171
telemt_pool_swap_total 10
telemt_pool_force_close_total 208
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 4368
telemt_me_writer_restored_same_endpoint_total 4206
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 216267
telemt_user_connections_current{user="hello"} 556
telemt_user_octets_from_client{user="hello"} 24888313384 (23.18 GB)
telemt_user_octets_to_client{user="hello"} 127333673580 (118.59 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 76
```