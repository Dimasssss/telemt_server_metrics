# Server Metrics 2026-03-06 22:47:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 16742.1 (4h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 261849
telemt_connections_bad_total 2243
telemt_handshake_timeouts_total 9184
telemt_upstream_connect_attempt_total 29843
telemt_upstream_connect_success_total 29476
telemt_upstream_connect_fail_total 236
telemt_upstream_connect_attempts_per_request{bucket="1"} 29712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19673
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 68
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 236
telemt_me_keepalive_timeout_total 1156
telemt_me_reconnect_attempts_total 10463
telemt_me_reconnect_success_total 10263
telemt_me_reader_eof_total 12858
telemt_me_idle_close_by_peer_total 12858
telemt_me_route_drop_no_conn_total 101115
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 139
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 831
telemt_desync_full_logged_total 244
telemt_desync_suppressed_total 587
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 333
telemt_desync_frames_bucket_total{bucket="gt_10"} 257
telemt_pool_swap_total 5
telemt_pool_force_close_total 320
telemt_pool_stale_pick_total 173
telemt_me_writer_removed_unexpected_total 12967
telemt_me_writer_restored_same_endpoint_total 10247
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2730
telemt_me_writer_removed_unexpected_minus_restored_total 2710
telemt_user_connections_total{user="hello"} 236350
telemt_user_connections_current{user="hello"} 457
telemt_user_octets_from_client{user="hello"} 3769884244 (3.51 GB)
telemt_user_octets_to_client{user="hello"} 104495927304 (97.32 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 16742.1 (4h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107218
telemt_connections_bad_total 99
telemt_handshake_timeouts_total 9685
telemt_upstream_connect_attempt_total 38932
telemt_upstream_connect_success_total 38931
telemt_upstream_connect_attempts_per_request{bucket="1"} 38931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23961
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 559
telemt_me_reconnect_attempts_total 17153
telemt_me_reconnect_success_total 17107
telemt_me_reader_eof_total 19602
telemt_me_idle_close_by_peer_total 19599
telemt_me_route_drop_no_conn_total 37614
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 143
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 678
telemt_desync_full_logged_total 183
telemt_desync_suppressed_total 495
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 319
telemt_desync_frames_bucket_total{bucket="gt_10"} 248
telemt_pool_swap_total 8
telemt_pool_force_close_total 334
telemt_pool_stale_pick_total 37
telemt_me_writer_removed_unexpected_total 19607
telemt_me_writer_restored_same_endpoint_total 17105
telemt_me_async_recovery_trigger_total 2721
telemt_me_writer_removed_unexpected_minus_restored_total 2502
telemt_user_connections_total{user="hello"} 91828
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 1376282376 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 33882067168 (31.56 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 16741.9 (4h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204298
telemt_connections_bad_total 871
telemt_handshake_timeouts_total 3264
telemt_upstream_connect_attempt_total 31147
telemt_upstream_connect_success_total 30996
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 31040
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16211
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 1178
telemt_me_reconnect_attempts_total 12195
telemt_me_reconnect_success_total 12159
telemt_me_reader_eof_total 13568
telemt_me_idle_close_by_peer_total 13565
telemt_me_route_drop_no_conn_total 77169
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 140
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 913
telemt_desync_full_logged_total 228
telemt_desync_suppressed_total 685
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 368
telemt_desync_frames_bucket_total{bucket="gt_10"} 374
telemt_pool_swap_total 9
telemt_pool_force_close_total 282
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 13688
telemt_me_writer_restored_same_endpoint_total 12152
telemt_me_async_recovery_trigger_total 8038
telemt_me_writer_removed_unexpected_minus_restored_total 1536
telemt_user_connections_total{user="hello"} 189703
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 13629627156 (12.69 GB)
telemt_user_octets_to_client{user="hello"} 57241360696 (53.31 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 16742.4 (4h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203009
telemt_connections_bad_total 55016
telemt_handshake_timeouts_total 15963
telemt_upstream_connect_attempt_total 28104
telemt_upstream_connect_success_total 28029
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 28056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15933
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 548
telemt_me_reconnect_attempts_total 8991
telemt_me_reconnect_success_total 8972
telemt_me_reader_eof_total 12044
telemt_me_idle_close_by_peer_total 12043
telemt_me_route_drop_no_conn_total 52850
telemt_me_single_endpoint_shadow_rotate_total 140
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 9
telemt_pool_force_close_total 332
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 12049
telemt_me_writer_restored_same_endpoint_total 8967
telemt_me_writer_removed_unexpected_minus_restored_total 3082
telemt_user_connections_total{user="hello"} 128602
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 1631395684 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 41680225656 (38.82 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 16740.7 (4h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176915
telemt_connections_bad_total 459
telemt_handshake_timeouts_total 1439
telemt_upstream_connect_attempt_total 25873
telemt_upstream_connect_success_total 25739
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 25758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15127
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 181
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 841
telemt_me_reconnect_attempts_total 7755
telemt_me_reconnect_success_total 7725
telemt_me_reader_eof_total 10406
telemt_me_idle_close_by_peer_total 10405
telemt_me_route_drop_no_conn_total 60955
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 136
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
telemt_me_writer_removed_unexpected_total 10471
telemt_me_writer_restored_same_endpoint_total 7723
telemt_me_writer_removed_unexpected_minus_restored_total 2748
telemt_user_connections_total{user="hello"} 161948
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 10015615504 (9.33 GB)
telemt_user_octets_to_client{user="hello"} 54348926472 (50.62 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 21
```