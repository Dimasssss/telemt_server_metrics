# Server Metrics 2026-03-06 22:36:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 16127.7 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257898
telemt_connections_bad_total 2243
telemt_handshake_timeouts_total 9157
telemt_upstream_connect_attempt_total 26675
telemt_upstream_connect_success_total 26453
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 26546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17774
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 63
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 1104
telemt_me_reconnect_attempts_total 8292
telemt_me_reconnect_success_total 8230
telemt_me_reader_eof_total 10733
telemt_me_idle_close_by_peer_total 10733
telemt_me_route_drop_no_conn_total 98981
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 131
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 824
telemt_desync_full_logged_total 241
telemt_desync_suppressed_total 583
telemt_desync_frames_bucket_total{bucket="1_2"} 240
telemt_desync_frames_bucket_total{bucket="3_10"} 330
telemt_desync_frames_bucket_total{bucket="gt_10"} 254
telemt_pool_swap_total 5
telemt_pool_force_close_total 320
telemt_pool_stale_pick_total 170
telemt_me_writer_removed_unexpected_total 10841
telemt_me_writer_restored_same_endpoint_total 8223
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 287
telemt_me_writer_removed_unexpected_minus_restored_total 2617
telemt_user_connections_total{user="hello"} 232652
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 3638762632 (3.39 GB)
telemt_user_octets_to_client{user="hello"} 98313744196 (91.56 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 16127.7 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104805
telemt_connections_bad_total 98
telemt_handshake_timeouts_total 9094
telemt_upstream_connect_attempt_total 32173
telemt_upstream_connect_success_total 32172
telemt_upstream_connect_attempts_per_request{bucket="1"} 32172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22967
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 526
telemt_me_reconnect_attempts_total 11368
telemt_me_reconnect_success_total 11349
telemt_me_reader_eof_total 15431
telemt_me_idle_close_by_peer_total 15428
telemt_me_route_drop_no_conn_total 37180
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 136
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 671
telemt_desync_full_logged_total 180
telemt_desync_suppressed_total 491
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 314
telemt_desync_frames_bucket_total{bucket="gt_10"} 246
telemt_pool_swap_total 7
telemt_pool_force_close_total 299
telemt_pool_stale_pick_total 37
telemt_me_writer_removed_unexpected_total 15431
telemt_me_writer_restored_same_endpoint_total 11347
telemt_me_async_recovery_trigger_total 276
telemt_me_writer_removed_unexpected_minus_restored_total 4084
telemt_user_connections_total{user="hello"} 90112
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 1364925196 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 32243514948 (30.03 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 16127.7 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201108
telemt_connections_bad_total 863
telemt_handshake_timeouts_total 3236
telemt_upstream_connect_attempt_total 26016
telemt_upstream_connect_success_total 25866
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 25909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14755
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1104
telemt_me_reconnect_attempts_total 7813
telemt_me_reconnect_success_total 7780
telemt_me_reader_eof_total 9809
telemt_me_idle_close_by_peer_total 9806
telemt_me_route_drop_no_conn_total 76193
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 132
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 910
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 685
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 368
telemt_desync_frames_bucket_total{bucket="gt_10"} 371
telemt_pool_swap_total 8
telemt_pool_force_close_total 276
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 9914
telemt_me_writer_restored_same_endpoint_total 7773
telemt_me_async_recovery_trigger_total 713
telemt_me_writer_removed_unexpected_minus_restored_total 2141
telemt_user_connections_total{user="hello"} 186578
telemt_user_connections_current{user="hello"} 253
telemt_user_octets_from_client{user="hello"} 13153367620 (12.25 GB)
telemt_user_octets_to_client{user="hello"} 56650049116 (52.76 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 16127.9 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199803
telemt_connections_bad_total 54473
telemt_handshake_timeouts_total 15948
telemt_upstream_connect_attempt_total 27346
telemt_upstream_connect_success_total 27273
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 27299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15449
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 530
telemt_me_reconnect_attempts_total 8850
telemt_me_reconnect_success_total 8830
telemt_me_reader_eof_total 11853
telemt_me_idle_close_by_peer_total 11852
telemt_me_route_drop_no_conn_total 51616
telemt_me_single_endpoint_shadow_rotate_total 132
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 8
telemt_pool_force_close_total 307
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 11858
telemt_me_writer_restored_same_endpoint_total 8825
telemt_me_writer_removed_unexpected_minus_restored_total 3033
telemt_user_connections_total{user="hello"} 125968
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 1621981480 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 40091121516 (37.34 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 16126.4 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173680
telemt_connections_bad_total 459
telemt_handshake_timeouts_total 1319
telemt_upstream_connect_attempt_total 24445
telemt_upstream_connect_success_total 24313
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 24332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14344
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 822
telemt_me_reconnect_attempts_total 7198
telemt_me_reconnect_success_total 7169
telemt_me_reader_eof_total 9669
telemt_me_idle_close_by_peer_total 9668
telemt_me_route_drop_no_conn_total 60001
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 128
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 733
telemt_desync_full_logged_total 184
telemt_desync_suppressed_total 549
telemt_desync_frames_bucket_total{bucket="1_2"} 259
telemt_desync_frames_bucket_total{bucket="3_10"} 235
telemt_desync_frames_bucket_total{bucket="gt_10"} 239
telemt_pool_swap_total 8
telemt_pool_force_close_total 319
telemt_pool_stale_pick_total 203
telemt_me_writer_removed_unexpected_total 9733
telemt_me_writer_restored_same_endpoint_total 7167
telemt_me_writer_removed_unexpected_minus_restored_total 2566
telemt_user_connections_total{user="hello"} 158932
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 9887149348 (9.21 GB)
telemt_user_octets_to_client{user="hello"} 53602992172 (49.92 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 37
```