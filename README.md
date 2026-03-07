# Server Metrics 2026-03-07 00:55:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 24438.2 (6h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 306117
telemt_connections_bad_total 3493
telemt_handshake_timeouts_total 9413
telemt_upstream_connect_attempt_total 70372
telemt_upstream_connect_success_total 68431
telemt_upstream_connect_fail_total 1804
telemt_upstream_connect_attempts_per_request{bucket="1"} 70235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 90
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1804
telemt_me_keepalive_timeout_total 1645
telemt_me_reconnect_attempts_total 40438
telemt_me_reconnect_success_total 38696
telemt_me_reader_eof_total 41383
telemt_me_idle_close_by_peer_total 41383
telemt_me_route_drop_no_conn_total 116958
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 202
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1006
telemt_desync_full_logged_total 273
telemt_desync_suppressed_total 733
telemt_desync_frames_bucket_total{bucket="1_2"} 279
telemt_desync_frames_bucket_total{bucket="3_10"} 452
telemt_desync_frames_bucket_total{bucket="gt_10"} 275
telemt_pool_swap_total 11
telemt_pool_force_close_total 514
telemt_pool_stale_pick_total 187
telemt_me_writer_removed_unexpected_total 41496
telemt_me_writer_restored_same_endpoint_total 38585
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 33338
telemt_me_writer_removed_unexpected_minus_restored_total 2806
telemt_user_connections_total{user="hello"} 278060
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 4249169700 (3.96 GB)
telemt_user_octets_to_client{user="hello"} 121485954680 (113.14 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 24438.2 (6h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131208
telemt_connections_bad_total 118
telemt_handshake_timeouts_total 15756
telemt_upstream_connect_attempt_total 138925
telemt_upstream_connect_success_total 138922
telemt_upstream_connect_attempts_per_request{bucket="1"} 138922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 101794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37096
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 1200
telemt_me_reconnect_attempts_total 104277
telemt_me_reconnect_success_total 103994
telemt_me_reader_eof_total 95336
telemt_me_idle_close_by_peer_total 95331
telemt_me_route_drop_no_conn_total 42311
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 213
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 809
telemt_desync_full_logged_total 214
telemt_desync_suppressed_total 595
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 407
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 17
telemt_pool_force_close_total 1029
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 95365
telemt_me_writer_restored_same_endpoint_total 103992
telemt_me_async_recovery_trigger_total 33331
telemt_user_connections_total{user="hello"} 108884
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 1564875016 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 37693351240 (35.10 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 24438.1 (6h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236712
telemt_connections_bad_total 1241
telemt_handshake_timeouts_total 3585
telemt_upstream_connect_attempt_total 105108
telemt_upstream_connect_success_total 104933
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 104997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35865
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 2135
telemt_me_reconnect_attempts_total 75022
telemt_me_reconnect_success_total 74957
telemt_me_reader_eof_total 76940
telemt_me_idle_close_by_peer_total 76935
telemt_me_route_drop_no_conn_total 89303
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 201
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1045
telemt_desync_full_logged_total 267
telemt_desync_suppressed_total 778
telemt_desync_frames_bucket_total{bucket="1_2"} 198
telemt_desync_frames_bucket_total{bucket="3_10"} 429
telemt_desync_frames_bucket_total{bucket="gt_10"} 418
telemt_pool_swap_total 14
telemt_pool_force_close_total 362
telemt_pool_stale_pick_total 126
telemt_me_writer_removed_unexpected_total 77108
telemt_me_writer_restored_same_endpoint_total 74950
telemt_me_async_recovery_trigger_total 99788
telemt_me_writer_removed_unexpected_minus_restored_total 2158
telemt_user_connections_total{user="hello"} 221076
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 20074795436 (18.70 GB)
telemt_user_octets_to_client{user="hello"} 63456684104 (59.10 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 24438.6 (6h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 240698
telemt_connections_bad_total 68587
telemt_handshake_timeouts_total 16758
telemt_upstream_connect_attempt_total 43483
telemt_upstream_connect_success_total 43398
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 43436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25767
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 844
telemt_me_reconnect_attempts_total 13896
telemt_me_reconnect_success_total 13869
telemt_me_reader_eof_total 18896
telemt_me_idle_close_by_peer_total 18894
telemt_me_route_drop_no_conn_total 64009
telemt_me_single_endpoint_shadow_rotate_total 208
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 215
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 13
telemt_pool_force_close_total 453
telemt_pool_stale_pick_total 474
telemt_me_writer_removed_unexpected_total 18901
telemt_me_writer_restored_same_endpoint_total 13864
telemt_me_writer_removed_unexpected_minus_restored_total 5037
telemt_user_connections_total{user="hello"} 151357
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 1733435932 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 49286606292 (45.90 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 24439.2 (6h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207521
telemt_connections_bad_total 509
telemt_handshake_timeouts_total 2417
telemt_upstream_connect_attempt_total 40189
telemt_upstream_connect_success_total 40037
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 40056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24084
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 1133
telemt_me_reconnect_attempts_total 11722
telemt_me_reconnect_success_total 11689
telemt_me_reader_eof_total 15923
telemt_me_idle_close_by_peer_total 15921
telemt_me_route_drop_no_conn_total 69505
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 199
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 796
telemt_desync_full_logged_total 205
telemt_desync_suppressed_total 591
telemt_desync_frames_bucket_total{bucket="1_2"} 272
telemt_desync_frames_bucket_total{bucket="3_10"} 261
telemt_desync_frames_bucket_total{bucket="gt_10"} 263
telemt_pool_swap_total 14
telemt_pool_force_close_total 428
telemt_pool_stale_pick_total 215
telemt_me_writer_removed_unexpected_total 15990
telemt_me_writer_restored_same_endpoint_total 11685
telemt_me_writer_removed_unexpected_minus_restored_total 4305
telemt_user_connections_total{user="hello"} 190611
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 10160223592 (9.46 GB)
telemt_user_octets_to_client{user="hello"} 67612824492 (62.97 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 25
```