# Server Metrics 2026-03-05 00:42:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 13769.9 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113314
telemt_connections_bad_total 3828
telemt_handshake_timeouts_total 815
telemt_upstream_connect_attempt_total 20438
telemt_upstream_connect_success_total 20257
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 20256
telemt_upstream_connect_attempts_per_request{bucket="2"} 60
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7248
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 44
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 594
telemt_me_reconnect_attempts_total 10059
telemt_me_reconnect_success_total 10047
telemt_me_reader_eof_total 10443
telemt_me_idle_close_by_peer_total 10442
telemt_me_route_drop_no_conn_total 30183
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 63
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 134
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 54
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 69
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 10502
telemt_me_writer_restored_same_endpoint_total 10027
telemt_me_writer_removed_unexpected_minus_restored_total 475
telemt_user_connections_total{user="hello"} 96944
telemt_user_connections_current{user="hello"} 385
telemt_user_octets_from_client{user="hello"} 2920882352 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 52378880088 (48.78 GB)
telemt_user_unique_ips_current{user="hello"} 41
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 13764.7 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42758
telemt_connections_bad_total 787
telemt_handshake_timeouts_total 1050
telemt_upstream_connect_attempt_total 15553
telemt_upstream_connect_success_total 15229
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 15219
telemt_upstream_connect_attempts_per_request{bucket="2"} 74
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5053
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 1034
telemt_me_reconnect_attempts_total 6009
telemt_me_reconnect_success_total 5982
telemt_me_reader_eof_total 6075
telemt_me_idle_close_by_peer_total 6074
telemt_me_route_drop_no_conn_total 13115
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 62
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 138
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_removed_unexpected_total 6179
telemt_me_writer_restored_same_endpoint_total 5957
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 38598
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 339244104 (323.53 MB)
telemt_user_octets_to_client{user="hello"} 10447424184 (9.73 GB)
telemt_user_unique_ips_current{user="hello"} 13
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 13761.4 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99231
telemt_connections_bad_total 1392
telemt_handshake_timeouts_total 702
telemt_upstream_connect_attempt_total 6611
telemt_upstream_connect_success_total 6553
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 6553
telemt_upstream_connect_attempts_per_request{bucket="2"} 21
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3128
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 415
telemt_me_reconnect_success_total 424
telemt_me_reader_eof_total 415
telemt_me_idle_close_by_peer_total 415
telemt_me_route_drop_no_conn_total 28202
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 173
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 4
telemt_pool_force_close_total 98
telemt_me_writer_removed_unexpected_total 415
telemt_me_writer_restored_same_endpoint_total 404
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 91253
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 1071559548 (1021.92 MB)
telemt_user_octets_to_client{user="hello"} 33844902672 (31.52 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 45809.6 (12h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 556721
telemt_connections_bad_total 82282
telemt_handshake_timeouts_total 14741
telemt_upstream_connect_attempt_total 21450
telemt_upstream_connect_success_total 21448
telemt_upstream_connect_attempts_per_request{bucket="1"} 21448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9020
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 263
telemt_me_reconnect_attempts_total 3147
telemt_me_reconnect_success_total 3127
telemt_me_reader_eof_total 3187
telemt_me_idle_close_by_peer_total 3187
telemt_me_route_drop_no_conn_total 186731
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 184
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 726
telemt_desync_full_logged_total 306
telemt_desync_suppressed_total 420
telemt_desync_frames_bucket_total{bucket="1_2"} 226
telemt_desync_frames_bucket_total{bucket="3_10"} 208
telemt_desync_frames_bucket_total{bucket="gt_10"} 292
telemt_pool_swap_total 18
telemt_pool_force_close_total 507
telemt_pool_stale_pick_total 22
telemt_me_writer_removed_unexpected_total 3188
telemt_me_writer_restored_same_endpoint_total 3100
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 431163
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 5865368996 (5.46 GB)
telemt_user_octets_to_client{user="hello"} 160195230208 (149.19 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 46168.6 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 540103
telemt_connections_bad_total 3858
telemt_handshake_timeouts_total 5917
telemt_upstream_connect_attempt_total 29715
telemt_upstream_connect_success_total 29554
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 29554
telemt_upstream_connect_attempts_per_request{bucket="2"} 64
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12273
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 444
telemt_me_reconnect_attempts_total 6561
telemt_me_reconnect_success_total 6539
telemt_me_reader_eof_total 6784
telemt_me_idle_close_by_peer_total 6783
telemt_me_route_drop_no_conn_total 237667
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 188
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 842
telemt_desync_full_logged_total 304
telemt_desync_suppressed_total 538
telemt_desync_frames_bucket_total{bucket="1_2"} 170
telemt_desync_frames_bucket_total{bucket="3_10"} 354
telemt_desync_frames_bucket_total{bucket="gt_10"} 318
telemt_pool_swap_total 10
telemt_pool_force_close_total 420
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 6789
telemt_me_writer_restored_same_endpoint_total 6517
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 489519
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 7391111236 (6.88 GB)
telemt_user_octets_to_client{user="hello"} 163874433028 (152.62 GB)
telemt_user_unique_ips_current{user="hello"} 29
```