# Server Metrics 2026-03-06 23:43:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 20131.1 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 282291
telemt_connections_bad_total 3004
telemt_handshake_timeouts_total 9273
telemt_upstream_connect_attempt_total 48126
telemt_upstream_connect_success_total 47063
telemt_upstream_connect_fail_total 925
telemt_upstream_connect_attempts_per_request{bucket="1"} 47988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30181
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 84
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 925
telemt_me_keepalive_timeout_total 1411
telemt_me_reconnect_attempts_total 23659
telemt_me_reconnect_success_total 22780
telemt_me_reader_eof_total 25505
telemt_me_idle_close_by_peer_total 25505
telemt_me_route_drop_no_conn_total 110543
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 166
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 978
telemt_desync_full_logged_total 263
telemt_desync_suppressed_total 715
telemt_desync_frames_bucket_total{bucket="1_2"} 270
telemt_desync_frames_bucket_total{bucket="3_10"} 434
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 7
telemt_pool_force_close_total 410
telemt_pool_stale_pick_total 179
telemt_me_writer_removed_unexpected_total 25617
telemt_me_writer_restored_same_endpoint_total 22722
telemt_me_writer_restored_fallback_total 52
telemt_me_async_recovery_trigger_total 16207
telemt_me_writer_removed_unexpected_minus_restored_total 2843
telemt_user_connections_total{user="hello"} 255525
telemt_user_connections_current{user="hello"} 318
telemt_user_octets_from_client{user="hello"} 4031366936 (3.75 GB)
telemt_user_octets_to_client{user="hello"} 115256606260 (107.34 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 20131.2 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118201
telemt_connections_bad_total 111
telemt_handshake_timeouts_total 12336
telemt_upstream_connect_attempt_total 78546
telemt_upstream_connect_success_total 78542
telemt_upstream_connect_attempts_per_request{bucket="1"} 78542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28950
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 889
telemt_me_reconnect_attempts_total 51258
telemt_me_reconnect_success_total 51054
telemt_me_reader_eof_total 49237
telemt_me_idle_close_by_peer_total 49233
telemt_me_route_drop_no_conn_total 39920
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 175
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 787
telemt_desync_full_logged_total 207
telemt_desync_suppressed_total 580
telemt_desync_frames_bucket_total{bucket="1_2"} 132
telemt_desync_frames_bucket_total{bucket="3_10"} 393
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 12
telemt_pool_force_close_total 699
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 49261
telemt_me_writer_restored_same_endpoint_total 51052
telemt_me_async_recovery_trigger_total 16202
telemt_user_connections_total{user="hello"} 99842
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 1492582752 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 36235019344 (33.75 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 20131.1 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217960
telemt_connections_bad_total 1092
telemt_handshake_timeouts_total 3523
telemt_upstream_connect_attempt_total 61278
telemt_upstream_connect_success_total 61117
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 61170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24778
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 1635
telemt_me_reconnect_attempts_total 37578
telemt_me_reconnect_success_total 37528
telemt_me_reader_eof_total 38825
telemt_me_idle_close_by_peer_total 38822
telemt_me_route_drop_no_conn_total 82631
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 169
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1026
telemt_desync_full_logged_total 255
telemt_desync_suppressed_total 771
telemt_desync_frames_bucket_total{bucket="1_2"} 192
telemt_desync_frames_bucket_total{bucket="3_10"} 422
telemt_desync_frames_bucket_total{bucket="gt_10"} 412
telemt_pool_swap_total 11
telemt_pool_force_close_total 316
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 38986
telemt_me_writer_restored_same_endpoint_total 37521
telemt_me_async_recovery_trigger_total 48448
telemt_me_writer_removed_unexpected_minus_restored_total 1465
telemt_user_connections_total{user="hello"} 202690
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 16192414608 (15.08 GB)
telemt_user_octets_to_client{user="hello"} 59577603444 (55.49 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 20131.5 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218061
telemt_connections_bad_total 58056
telemt_handshake_timeouts_total 16168
telemt_upstream_connect_attempt_total 34910
telemt_upstream_connect_success_total 34829
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 34863
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20363
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 695
telemt_me_reconnect_attempts_total 11144
telemt_me_reconnect_success_total 11122
telemt_me_reader_eof_total 15091
telemt_me_idle_close_by_peer_total 15089
telemt_me_route_drop_no_conn_total 59087
telemt_me_single_endpoint_shadow_rotate_total 171
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 199
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 115
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 11
telemt_pool_force_close_total 393
telemt_pool_stale_pick_total 453
telemt_me_writer_removed_unexpected_total 15096
telemt_me_writer_restored_same_endpoint_total 11117
telemt_me_writer_removed_unexpected_minus_restored_total 3979
telemt_user_connections_total{user="hello"} 140066
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 1664630292 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 46423692272 (43.24 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 20129.8 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190069
telemt_connections_bad_total 494
telemt_handshake_timeouts_total 1873
telemt_upstream_connect_attempt_total 31438
telemt_upstream_connect_success_total 31295
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 31314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18503
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 968
telemt_me_reconnect_attempts_total 9034
telemt_me_reconnect_success_total 9003
telemt_me_reader_eof_total 12146
telemt_me_idle_close_by_peer_total 12145
telemt_me_route_drop_no_conn_total 64108
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 165
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 756
telemt_desync_full_logged_total 192
telemt_desync_suppressed_total 564
telemt_desync_frames_bucket_total{bucket="1_2"} 264
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 247
telemt_pool_swap_total 12
telemt_pool_force_close_total 379
telemt_pool_stale_pick_total 215
telemt_me_writer_removed_unexpected_total 12213
telemt_me_writer_restored_same_endpoint_total 8999
telemt_me_writer_removed_unexpected_minus_restored_total 3214
telemt_user_connections_total{user="hello"} 174187
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 10063588716 (9.37 GB)
telemt_user_octets_to_client{user="hello"} 59758949068 (55.65 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 28
```