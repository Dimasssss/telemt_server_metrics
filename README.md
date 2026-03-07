# Server Metrics 2026-03-07 00:09:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 21668.5 (6h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 289705
telemt_connections_bad_total 3005
telemt_handshake_timeouts_total 9326
telemt_upstream_connect_attempt_total 55206
telemt_upstream_connect_success_total 53791
telemt_upstream_connect_fail_total 1278
telemt_upstream_connect_attempts_per_request{bucket="1"} 55069
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34779
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 87
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1278
telemt_me_keepalive_timeout_total 1487
telemt_me_reconnect_attempts_total 29046
telemt_me_reconnect_success_total 27821
telemt_me_reader_eof_total 30667
telemt_me_idle_close_by_peer_total 30667
telemt_me_route_drop_no_conn_total 112494
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 175
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 993
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 727
telemt_desync_frames_bucket_total{bucket="1_2"} 272
telemt_desync_frames_bucket_total{bucket="3_10"} 447
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 8
telemt_pool_force_close_total 435
telemt_pool_stale_pick_total 185
telemt_me_writer_removed_unexpected_total 30780
telemt_me_writer_restored_same_endpoint_total 27742
telemt_me_writer_restored_fallback_total 73
telemt_me_async_recovery_trigger_total 22322
telemt_me_writer_removed_unexpected_minus_restored_total 2965
telemt_user_connections_total{user="hello"} 262712
telemt_user_connections_current{user="hello"} 351
telemt_user_octets_from_client{user="hello"} 4130757404 (3.85 GB)
telemt_user_octets_to_client{user="hello"} 117590159616 (109.51 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 21668.6 (6h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122388
telemt_connections_bad_total 112
telemt_handshake_timeouts_total 13579
telemt_upstream_connect_attempt_total 101328
telemt_upstream_connect_success_total 101325
telemt_upstream_connect_attempts_per_request{bucket="1"} 101325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69775
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31519
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 1017
telemt_me_reconnect_attempts_total 71229
telemt_me_reconnect_success_total 70973
telemt_me_reader_eof_total 67438
telemt_me_idle_close_by_peer_total 67433
telemt_me_route_drop_no_conn_total 40566
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 186
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 805
telemt_desync_full_logged_total 211
telemt_desync_suppressed_total 594
telemt_desync_frames_bucket_total{bucket="1_2"} 138
telemt_desync_frames_bucket_total{bucket="3_10"} 405
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 13
telemt_pool_force_close_total 771
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 67465
telemt_me_writer_restored_same_endpoint_total 70971
telemt_me_async_recovery_trigger_total 22316
telemt_user_connections_total{user="hello"} 102688
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 1516915028 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 36568524164 (34.06 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 21668.5 (6h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223919
telemt_connections_bad_total 1128
telemt_handshake_timeouts_total 3546
telemt_upstream_connect_attempt_total 78136
telemt_upstream_connect_success_total 77967
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 78023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28878
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 1820
telemt_me_reconnect_attempts_total 52068
telemt_me_reconnect_success_total 52013
telemt_me_reader_eof_total 54170
telemt_me_idle_close_by_peer_total 54165
telemt_me_route_drop_no_conn_total 85144
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 177
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
telemt_me_writer_removed_unexpected_total 54332
telemt_me_writer_restored_same_endpoint_total 52006
telemt_me_async_recovery_trigger_total 66772
telemt_me_writer_removed_unexpected_minus_restored_total 2326
telemt_user_connections_total{user="hello"} 208526
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 17650792932 (16.44 GB)
telemt_user_octets_to_client{user="hello"} 60513602788 (56.36 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 21668.9 (6h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223616
telemt_connections_bad_total 59744
telemt_handshake_timeouts_total 16186
telemt_upstream_connect_attempt_total 37339
telemt_upstream_connect_success_total 37258
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 37292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21891
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 737
telemt_me_reconnect_attempts_total 11583
telemt_me_reconnect_success_total 11560
telemt_me_reader_eof_total 15656
telemt_me_idle_close_by_peer_total 15654
telemt_me_route_drop_no_conn_total 60428
telemt_me_single_endpoint_shadow_rotate_total 180
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 207
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 118
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 12
telemt_pool_force_close_total 417
telemt_pool_stale_pick_total 466
telemt_me_writer_removed_unexpected_total 15661
telemt_me_writer_restored_same_endpoint_total 11555
telemt_me_writer_removed_unexpected_minus_restored_total 4106
telemt_user_connections_total{user="hello"} 143825
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 1689348492 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 47306931896 (44.06 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 21667.3 (6h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195896
telemt_connections_bad_total 502
telemt_handshake_timeouts_total 2055
telemt_upstream_connect_attempt_total 34818
telemt_upstream_connect_success_total 34671
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 34690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20822
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 1018
telemt_me_reconnect_attempts_total 10130
telemt_me_reconnect_success_total 10097
telemt_me_reader_eof_total 13758
telemt_me_idle_close_by_peer_total 13756
telemt_me_route_drop_no_conn_total 66295
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 173
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 758
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 564
telemt_desync_frames_bucket_total{bucket="1_2"} 265
telemt_desync_frames_bucket_total{bucket="3_10"} 246
telemt_desync_frames_bucket_total{bucket="gt_10"} 247
telemt_pool_swap_total 12
telemt_pool_force_close_total 379
telemt_pool_stale_pick_total 215
telemt_me_writer_removed_unexpected_total 13825
telemt_me_writer_restored_same_endpoint_total 10093
telemt_me_writer_removed_unexpected_minus_restored_total 3732
telemt_user_connections_total{user="hello"} 179660
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 10087939940 (9.40 GB)
telemt_user_octets_to_client{user="hello"} 61305737220 (57.10 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 24
```