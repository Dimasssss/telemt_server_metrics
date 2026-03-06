# Server Metrics 2026-03-06 06:25:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 29054.4 (8h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 256179
telemt_connections_bad_total 16089
telemt_handshake_timeouts_total 3687
telemt_upstream_connect_attempt_total 29076
telemt_upstream_connect_success_total 28821
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 28821
telemt_upstream_connect_attempts_per_request{bucket="2"} 117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11007
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 296
telemt_me_reconnect_attempts_total 10238
telemt_me_reconnect_success_total 10199
telemt_me_reader_eof_total 10545
telemt_me_idle_close_by_peer_total 10545
telemt_me_route_drop_no_conn_total 88173
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 121
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 786
telemt_desync_full_logged_total 251
telemt_desync_suppressed_total 535
telemt_desync_frames_bucket_total{bucket="1_2"} 220
telemt_desync_frames_bucket_total{bucket="3_10"} 275
telemt_desync_frames_bucket_total{bucket="gt_10"} 291
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 10547
telemt_me_writer_restored_same_endpoint_total 10193
telemt_me_writer_removed_unexpected_minus_restored_total 354
telemt_user_connections_total{user="hello"} 225515
telemt_user_connections_current{user="hello"} 785
telemt_user_octets_from_client{user="hello"} 6679589592 (6.22 GB)
telemt_user_octets_to_client{user="hello"} 82396633916 (76.74 GB)
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 29049.9 (8h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107465
telemt_connections_bad_total 154
telemt_handshake_timeouts_total 9646
telemt_upstream_connect_attempt_total 24988
telemt_upstream_connect_success_total 24986
telemt_upstream_connect_attempts_per_request{bucket="1"} 24986
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10863
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 298
telemt_me_reconnect_attempts_total 6775
telemt_me_reconnect_success_total 6747
telemt_me_reader_eof_total 6898
telemt_me_idle_close_by_peer_total 6898
telemt_me_route_drop_no_conn_total 30958
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 125
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 352
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 241
telemt_desync_frames_bucket_total{bucket="1_2"} 100
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_pool_swap_total 10
telemt_pool_force_close_total 197
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6899
telemt_me_writer_restored_same_endpoint_total 6741
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 95728
telemt_user_connections_current{user="hello"} 309
telemt_user_octets_from_client{user="hello"} 954195668 (909.99 MB)
telemt_user_octets_to_client{user="hello"} 32124874104 (29.92 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 29047.2 (8h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183280
telemt_connections_bad_total 1716
telemt_handshake_timeouts_total 4457
telemt_upstream_connect_attempt_total 32421
telemt_upstream_connect_success_total 32192
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 32192
telemt_upstream_connect_attempts_per_request{bucket="2"} 102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19237
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12902
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 447
telemt_me_reconnect_attempts_total 11793
telemt_me_reconnect_success_total 11755
telemt_me_reader_eof_total 12285
telemt_me_idle_close_by_peer_total 12284
telemt_me_route_drop_no_conn_total 54291
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 122
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 349
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 234
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 12311
telemt_me_writer_restored_same_endpoint_total 11733
telemt_me_writer_restored_fallback_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 564
telemt_user_connections_total{user="hello"} 162873
telemt_user_connections_current{user="hello"} 495
telemt_user_octets_from_client{user="hello"} 1612000680 (1.50 GB)
telemt_user_octets_to_client{user="hello"} 53697303196 (50.01 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 29044.0 (8h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145542
telemt_connections_bad_total 12402
telemt_handshake_timeouts_total 6391
telemt_upstream_connect_attempt_total 21196
telemt_upstream_connect_success_total 21123
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 21123
telemt_upstream_connect_attempts_per_request{bucket="2"} 35
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12624
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8497
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4845
telemt_me_reconnect_success_total 4814
telemt_me_reader_eof_total 4984
telemt_me_idle_close_by_peer_total 4984
telemt_me_route_drop_no_conn_total 48318
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 119
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 332
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 222
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 9
telemt_pool_force_close_total 214
telemt_me_writer_removed_unexpected_total 4985
telemt_me_writer_restored_same_endpoint_total 4807
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 120786
telemt_user_connections_current{user="hello"} 362
telemt_user_octets_from_client{user="hello"} 1843694616 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 41712662904 (38.85 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 29042.8 (8h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159709
telemt_connections_bad_total 3274
telemt_handshake_timeouts_total 899
telemt_upstream_connect_attempt_total 20454
telemt_upstream_connect_success_total 20407
telemt_upstream_connect_attempts_per_request{bucket="1"} 20407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8226
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 316
telemt_me_reconnect_attempts_total 3701
telemt_me_reconnect_success_total 3685
telemt_me_reader_eof_total 3803
telemt_me_idle_close_by_peer_total 3802
telemt_me_route_drop_no_conn_total 59765
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 126
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 335
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 197
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 163
telemt_desync_frames_bucket_total{bucket="gt_10"} 110
telemt_pool_swap_total 9
telemt_pool_force_close_total 196
telemt_pool_stale_pick_total 4
telemt_me_writer_removed_unexpected_total 3818
telemt_me_writer_restored_same_endpoint_total 3678
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 152606
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 24108392280 (22.45 GB)
telemt_user_octets_to_client{user="hello"} 94780528524 (88.27 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 72
```