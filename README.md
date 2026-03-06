# Server Metrics 2026-03-06 22:52:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 17049.3 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 263742
telemt_connections_bad_total 2243
telemt_handshake_timeouts_total 9204
telemt_upstream_connect_attempt_total 31554
telemt_upstream_connect_success_total 31128
telemt_upstream_connect_fail_total 292
telemt_upstream_connect_attempts_per_request{bucket="1"} 31420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20655
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 71
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 292
telemt_me_keepalive_timeout_total 1179
telemt_me_reconnect_attempts_total 11681
telemt_me_reconnect_success_total 11426
telemt_me_reader_eof_total 14223
telemt_me_idle_close_by_peer_total 14223
telemt_me_route_drop_no_conn_total 103035
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 139
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 836
telemt_desync_full_logged_total 245
telemt_desync_suppressed_total 591
telemt_desync_frames_bucket_total{bucket="1_2"} 242
telemt_desync_frames_bucket_total{bucket="3_10"} 337
telemt_desync_frames_bucket_total{bucket="gt_10"} 257
telemt_pool_swap_total 5
telemt_pool_force_close_total 320
telemt_pool_stale_pick_total 173
telemt_me_writer_removed_unexpected_total 14332
telemt_me_writer_restored_same_endpoint_total 11407
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 3952
telemt_me_writer_removed_unexpected_minus_restored_total 2912
telemt_user_connections_total{user="hello"} 238175
telemt_user_connections_current{user="hello"} 458
telemt_user_octets_from_client{user="hello"} 3811155820 (3.55 GB)
telemt_user_octets_to_client{user="hello"} 107187465740 (99.83 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 17049.2 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108159
telemt_connections_bad_total 99
telemt_handshake_timeouts_total 9940
telemt_upstream_connect_attempt_total 42246
telemt_upstream_connect_success_total 42244
telemt_upstream_connect_attempts_per_request{bucket="1"} 42244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24308
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 636
telemt_me_reconnect_attempts_total 19913
telemt_me_reconnect_success_total 19845
telemt_me_reader_eof_total 22439
telemt_me_idle_close_by_peer_total 22436
telemt_me_route_drop_no_conn_total 37970
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 144
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 680
telemt_desync_full_logged_total 184
telemt_desync_suppressed_total 496
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 321
telemt_desync_frames_bucket_total{bucket="gt_10"} 248
telemt_pool_swap_total 8
telemt_pool_force_close_total 334
telemt_pool_stale_pick_total 37
telemt_me_writer_removed_unexpected_total 22452
telemt_me_writer_restored_same_endpoint_total 19843
telemt_me_async_recovery_trigger_total 3942
telemt_me_writer_removed_unexpected_minus_restored_total 2609
telemt_user_connections_total{user="hello"} 92505
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 1382701060 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 33989600304 (31.66 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 17049.0 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205715
telemt_connections_bad_total 880
telemt_handshake_timeouts_total 3281
telemt_upstream_connect_attempt_total 33116
telemt_upstream_connect_success_total 32962
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 33007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16943
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 1223
telemt_me_reconnect_attempts_total 13795
telemt_me_reconnect_success_total 13758
telemt_me_reader_eof_total 15251
telemt_me_idle_close_by_peer_total 15248
telemt_me_route_drop_no_conn_total 78588
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 140
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 934
telemt_desync_full_logged_total 231
telemt_desync_suppressed_total 703
telemt_desync_frames_bucket_total{bucket="1_2"} 179
telemt_desync_frames_bucket_total{bucket="3_10"} 371
telemt_desync_frames_bucket_total{bucket="gt_10"} 384
telemt_pool_swap_total 9
telemt_pool_force_close_total 282
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 15379
telemt_me_writer_restored_same_endpoint_total 13751
telemt_me_async_recovery_trigger_total 11701
telemt_me_writer_removed_unexpected_minus_restored_total 1628
telemt_user_connections_total{user="hello"} 191071
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 13824991948 (12.88 GB)
telemt_user_octets_to_client{user="hello"} 57510829304 (53.56 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 17049.5 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204384
telemt_connections_bad_total 55298
telemt_handshake_timeouts_total 15967
telemt_upstream_connect_attempt_total 28501
telemt_upstream_connect_success_total 28427
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 28454
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16181
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 559
telemt_me_reconnect_attempts_total 9028
telemt_me_reconnect_success_total 9008
telemt_me_reader_eof_total 12084
telemt_me_idle_close_by_peer_total 12083
telemt_me_route_drop_no_conn_total 54188
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
telemt_me_writer_removed_unexpected_total 12090
telemt_me_writer_restored_same_endpoint_total 9003
telemt_me_writer_removed_unexpected_minus_restored_total 3087
telemt_user_connections_total{user="hello"} 129662
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 1634341576 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 41762422768 (38.89 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 17047.9 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 178038
telemt_connections_bad_total 460
telemt_handshake_timeouts_total 1475
telemt_upstream_connect_attempt_total 26629
telemt_upstream_connect_success_total 26495
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 26514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15627
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 868
telemt_me_reconnect_attempts_total 8057
telemt_me_reconnect_success_total 8026
telemt_me_reader_eof_total 10878
telemt_me_idle_close_by_peer_total 10877
telemt_me_route_drop_no_conn_total 61368
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
telemt_me_writer_removed_unexpected_total 10945
telemt_me_writer_restored_same_endpoint_total 8024
telemt_me_writer_removed_unexpected_minus_restored_total 2921
telemt_user_connections_total{user="hello"} 162956
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 10019987868 (9.33 GB)
telemt_user_octets_to_client{user="hello"} 54724154104 (50.97 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 22
```