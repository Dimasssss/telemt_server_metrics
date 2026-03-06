# Server Metrics 2026-03-06 23:28:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 19204.4 (5h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 277743
telemt_connections_bad_total 2795
telemt_handshake_timeouts_total 9266
telemt_upstream_connect_attempt_total 43229
telemt_upstream_connect_success_total 42369
telemt_upstream_connect_fail_total 722
telemt_upstream_connect_attempts_per_request{bucket="1"} 43091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14871
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27276
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 84
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 722
telemt_me_keepalive_timeout_total 1334
telemt_me_reconnect_attempts_total 20083
telemt_me_reconnect_success_total 19406
telemt_me_reader_eof_total 22048
telemt_me_idle_close_by_peer_total 22048
telemt_me_route_drop_no_conn_total 109466
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 160
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 864
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 614
telemt_desync_frames_bucket_total{bucket="1_2"} 245
telemt_desync_frames_bucket_total{bucket="3_10"} 347
telemt_desync_frames_bucket_total{bucket="gt_10"} 272
telemt_pool_swap_total 6
telemt_pool_force_close_total 379
telemt_pool_stale_pick_total 176
telemt_me_writer_removed_unexpected_total 22158
telemt_me_writer_restored_same_endpoint_total 19361
telemt_me_writer_restored_fallback_total 39
telemt_me_async_recovery_trigger_total 12522
telemt_me_writer_removed_unexpected_minus_restored_total 2758
telemt_user_connections_total{user="hello"} 251270
telemt_user_connections_current{user="hello"} 395
telemt_user_octets_from_client{user="hello"} 3986988684 (3.71 GB)
telemt_user_octets_to_client{user="hello"} 114008620896 (106.18 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 19204.5 (5h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115351
telemt_connections_bad_total 100
telemt_handshake_timeouts_total 11623
telemt_upstream_connect_attempt_total 67533
telemt_upstream_connect_success_total 67531
telemt_upstream_connect_attempts_per_request{bucket="1"} 67531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27511
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 827
telemt_me_reconnect_attempts_total 41597
telemt_me_reconnect_success_total 41436
telemt_me_reader_eof_total 40702
telemt_me_idle_close_by_peer_total 40698
telemt_me_route_drop_no_conn_total 39619
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 167
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 709
telemt_desync_full_logged_total 193
telemt_desync_suppressed_total 516
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 336
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 11
telemt_pool_force_close_total 604
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 40725
telemt_me_writer_restored_same_endpoint_total 41434
telemt_me_async_recovery_trigger_total 12515
telemt_user_connections_total{user="hello"} 97787
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 1475975252 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 35649137788 (33.20 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 19204.3 (5h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213992
telemt_connections_bad_total 918
telemt_handshake_timeouts_total 3518
telemt_upstream_connect_attempt_total 52175
telemt_upstream_connect_success_total 52016
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 52067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22334
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 1520
telemt_me_reconnect_attempts_total 29846
telemt_me_reconnect_success_total 29800
telemt_me_reader_eof_total 30679
telemt_me_idle_close_by_peer_total 30676
telemt_me_route_drop_no_conn_total 81650
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 161
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 981
telemt_desync_full_logged_total 247
telemt_desync_suppressed_total 734
telemt_desync_frames_bucket_total{bucket="1_2"} 185
telemt_desync_frames_bucket_total{bucket="3_10"} 392
telemt_desync_frames_bucket_total{bucket="gt_10"} 404
telemt_pool_swap_total 11
telemt_pool_force_close_total 316
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 30834
telemt_me_writer_restored_same_endpoint_total 29793
telemt_me_async_recovery_trigger_total 37400
telemt_me_writer_removed_unexpected_minus_restored_total 1041
telemt_user_connections_total{user="hello"} 198978
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 15389739452 (14.33 GB)
telemt_user_octets_to_client{user="hello"} 58832350168 (54.79 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 19204.7 (5h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213980
telemt_connections_bad_total 57233
telemt_handshake_timeouts_total 16168
telemt_upstream_connect_attempt_total 32895
telemt_upstream_connect_success_total 32815
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 32848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18984
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 651
telemt_me_reconnect_attempts_total 10431
telemt_me_reconnect_success_total 10409
telemt_me_reader_eof_total 14039
telemt_me_idle_close_by_peer_total 14037
telemt_me_route_drop_no_conn_total 56903
telemt_me_single_endpoint_shadow_rotate_total 163
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 184
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 10
telemt_pool_force_close_total 368
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 14044
telemt_me_writer_restored_same_endpoint_total 10404
telemt_me_writer_removed_unexpected_minus_restored_total 3640
telemt_user_connections_total{user="hello"} 136972
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 1655986544 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 43850126124 (40.84 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 19203.0 (5h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 186250
telemt_connections_bad_total 476
telemt_handshake_timeouts_total 1754
telemt_upstream_connect_attempt_total 30027
telemt_upstream_connect_success_total 29887
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 29906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17694
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 198
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 946
telemt_me_reconnect_attempts_total 8788
telemt_me_reconnect_success_total 8757
telemt_me_reader_eof_total 11856
telemt_me_idle_close_by_peer_total 11855
telemt_me_route_drop_no_conn_total 63204
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 159
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 752
telemt_desync_full_logged_total 188
telemt_desync_suppressed_total 564
telemt_desync_frames_bucket_total{bucket="1_2"} 263
telemt_desync_frames_bucket_total{bucket="3_10"} 242
telemt_desync_frames_bucket_total{bucket="gt_10"} 247
telemt_pool_swap_total 11
telemt_pool_force_close_total 364
telemt_pool_stale_pick_total 215
telemt_me_writer_removed_unexpected_total 11923
telemt_me_writer_restored_same_endpoint_total 8753
telemt_me_writer_removed_unexpected_minus_restored_total 3170
telemt_user_connections_total{user="hello"} 170571
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 10053525808 (9.36 GB)
telemt_user_octets_to_client{user="hello"} 59127166868 (55.07 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 30
```