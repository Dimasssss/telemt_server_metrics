# Server Metrics 2026-03-07 00:14:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 21976.2 (6h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 291498
telemt_connections_bad_total 3006
telemt_handshake_timeouts_total 9336
telemt_upstream_connect_attempt_total 56479
telemt_upstream_connect_success_total 54989
telemt_upstream_connect_fail_total 1354
telemt_upstream_connect_attempts_per_request{bucket="1"} 56343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35620
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 87
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1354
telemt_me_keepalive_timeout_total 1502
telemt_me_reconnect_attempts_total 30014
telemt_me_reconnect_success_total 28715
telemt_me_reader_eof_total 31265
telemt_me_idle_close_by_peer_total 31265
telemt_me_route_drop_no_conn_total 112848
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 180
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 993
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 727
telemt_desync_frames_bucket_total{bucket="1_2"} 272
telemt_desync_frames_bucket_total{bucket="3_10"} 447
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 9
telemt_pool_force_close_total 474
telemt_pool_stale_pick_total 186
telemt_me_writer_removed_unexpected_total 31378
telemt_me_writer_restored_same_endpoint_total 28631
telemt_me_writer_restored_fallback_total 78
telemt_me_async_recovery_trigger_total 23546
telemt_me_writer_removed_unexpected_minus_restored_total 2669
telemt_user_connections_total{user="hello"} 264466
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 4139399748 (3.86 GB)
telemt_user_octets_to_client{user="hello"} 118319802732 (110.19 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 21976.3 (6h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123444
telemt_connections_bad_total 112
telemt_handshake_timeouts_total 13833
telemt_upstream_connect_attempt_total 104978
telemt_upstream_connect_success_total 104976
telemt_upstream_connect_attempts_per_request{bucket="1"} 104976
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 1034
telemt_me_reconnect_attempts_total 74480
telemt_me_reconnect_success_total 74222
telemt_me_reader_eof_total 69416
telemt_me_idle_close_by_peer_total 69411
telemt_me_route_drop_no_conn_total 40644
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 191
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 805
telemt_desync_full_logged_total 211
telemt_desync_suppressed_total 594
telemt_desync_frames_bucket_total{bucket="1_2"} 138
telemt_desync_frames_bucket_total{bucket="3_10"} 405
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 14
telemt_pool_force_close_total 854
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 69443
telemt_me_writer_restored_same_endpoint_total 74220
telemt_me_async_recovery_trigger_total 23540
telemt_user_connections_total{user="hello"} 103424
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 1522086788 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 36789974820 (34.26 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 21976.3 (6h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225503
telemt_connections_bad_total 1140
telemt_handshake_timeouts_total 3547
telemt_upstream_connect_attempt_total 81710
telemt_upstream_connect_success_total 81542
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 81599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29721
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 1866
telemt_me_reconnect_attempts_total 55121
telemt_me_reconnect_success_total 55065
telemt_me_reader_eof_total 57463
telemt_me_idle_close_by_peer_total 57458
telemt_me_route_drop_no_conn_total 85845
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 185
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1030
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 771
telemt_desync_frames_bucket_total{bucket="1_2"} 193
telemt_desync_frames_bucket_total{bucket="3_10"} 424
telemt_desync_frames_bucket_total{bucket="gt_10"} 413
telemt_pool_swap_total 11
telemt_pool_force_close_total 316
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 57627
telemt_me_writer_restored_same_endpoint_total 55058
telemt_me_async_recovery_trigger_total 70439
telemt_me_writer_removed_unexpected_minus_restored_total 2569
telemt_user_connections_total{user="hello"} 210079
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 17943526820 (16.71 GB)
telemt_user_octets_to_client{user="hello"} 60844265504 (56.67 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 21976.6 (6h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225398
telemt_connections_bad_total 60731
telemt_handshake_timeouts_total 16187
telemt_upstream_connect_attempt_total 38028
telemt_upstream_connect_success_total 37945
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 37981
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22332
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 749
telemt_me_reconnect_attempts_total 11817
telemt_me_reconnect_success_total 11794
telemt_me_reader_eof_total 15983
telemt_me_idle_close_by_peer_total 15981
telemt_me_route_drop_no_conn_total 61040
telemt_me_single_endpoint_shadow_rotate_total 187
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 207
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 118
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 12
telemt_pool_force_close_total 417
telemt_pool_stale_pick_total 467
telemt_me_writer_removed_unexpected_total 15988
telemt_me_writer_restored_same_endpoint_total 11789
telemt_me_writer_removed_unexpected_minus_restored_total 4199
telemt_user_connections_total{user="hello"} 144601
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 1698794576 (1.58 GB)
telemt_user_octets_to_client{user="hello"} 47887992648 (44.60 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 21975.1 (6h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197101
telemt_connections_bad_total 502
telemt_handshake_timeouts_total 2099
telemt_upstream_connect_attempt_total 35176
telemt_upstream_connect_success_total 35029
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 35048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21028
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 1032
telemt_me_reconnect_attempts_total 10160
telemt_me_reconnect_success_total 10128
telemt_me_reader_eof_total 13803
telemt_me_idle_close_by_peer_total 13801
telemt_me_route_drop_no_conn_total 66545
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 180
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 758
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 564
telemt_desync_frames_bucket_total{bucket="1_2"} 265
telemt_desync_frames_bucket_total{bucket="3_10"} 246
telemt_desync_frames_bucket_total{bucket="gt_10"} 247
telemt_pool_swap_total 13
telemt_pool_force_close_total 412
telemt_pool_stale_pick_total 215
telemt_me_writer_removed_unexpected_total 13870
telemt_me_writer_restored_same_endpoint_total 10124
telemt_me_writer_removed_unexpected_minus_restored_total 3746
telemt_user_connections_total{user="hello"} 180816
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 10096125308 (9.40 GB)
telemt_user_octets_to_client{user="hello"} 62882434568 (58.56 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 26
```