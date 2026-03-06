# Server Metrics 2026-03-06 08:03:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 34894.1 (9h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 373490
telemt_connections_bad_total 17022
telemt_handshake_timeouts_total 4113
telemt_upstream_connect_attempt_total 36081
telemt_upstream_connect_success_total 35727
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 35727
telemt_upstream_connect_attempts_per_request{bucket="2"} 159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13692
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 70
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_keepalive_timeout_total 378
telemt_me_reconnect_attempts_total 13071
telemt_me_reconnect_success_total 13021
telemt_me_reader_eof_total 13475
telemt_me_idle_close_by_peer_total 13475
telemt_me_route_drop_no_conn_total 132285
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 143
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1243
telemt_desync_full_logged_total 391
telemt_desync_suppressed_total 852
telemt_desync_frames_bucket_total{bucket="1_2"} 353
telemt_desync_frames_bucket_total{bucket="3_10"} 413
telemt_desync_frames_bucket_total{bucket="gt_10"} 477
telemt_pool_swap_total 5
telemt_pool_force_close_total 281
telemt_me_writer_removed_unexpected_total 13478
telemt_me_writer_restored_same_endpoint_total 13013
telemt_me_writer_removed_unexpected_minus_restored_total 465
telemt_user_connections_total{user="hello"} 331539
telemt_user_connections_current{user="hello"} 877
telemt_user_octets_from_client{user="hello"} 10453791956 (9.74 GB)
telemt_user_octets_to_client{user="hello"} 118518428904 (110.38 GB)
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 34889.4 (9h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165342
telemt_connections_bad_total 311
telemt_handshake_timeouts_total 18255
telemt_upstream_connect_attempt_total 27221
telemt_upstream_connect_success_total 27219
telemt_upstream_connect_attempts_per_request{bucket="1"} 27219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12048
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 325
telemt_me_reconnect_attempts_total 6827
telemt_me_reconnect_success_total 6794
telemt_me_reader_eof_total 6946
telemt_me_idle_close_by_peer_total 6946
telemt_me_route_drop_no_conn_total 48845
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 149
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 492
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 331
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 184
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 11
telemt_pool_force_close_total 238
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6947
telemt_me_writer_restored_same_endpoint_total 6787
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 143749
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 1686003156 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 45382388500 (42.27 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 34886.9 (9h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 289965
telemt_connections_bad_total 2047
telemt_handshake_timeouts_total 10771
telemt_upstream_connect_attempt_total 38034
telemt_upstream_connect_success_total 37744
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 37744
telemt_upstream_connect_attempts_per_request{bucket="2"} 131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15346
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 544
telemt_me_reconnect_attempts_total 14260
telemt_me_reconnect_success_total 14216
telemt_me_reader_eof_total 14870
telemt_me_idle_close_by_peer_total 14868
telemt_me_route_drop_no_conn_total 87782
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 142
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 796
telemt_desync_full_logged_total 239
telemt_desync_suppressed_total 557
telemt_desync_frames_bucket_total{bucket="1_2"} 156
telemt_desync_frames_bucket_total{bucket="3_10"} 291
telemt_desync_frames_bucket_total{bucket="gt_10"} 349
telemt_pool_swap_total 5
telemt_pool_force_close_total 173
telemt_pool_stale_pick_total 227
telemt_me_writer_removed_unexpected_total 14899
telemt_me_writer_restored_same_endpoint_total 14194
telemt_me_writer_restored_fallback_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 691
telemt_user_connections_total{user="hello"} 251260
telemt_user_connections_current{user="hello"} 614
telemt_user_octets_from_client{user="hello"} 2898911140 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 79532427668 (74.07 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 34883.5 (9h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219386
telemt_connections_bad_total 31123
telemt_handshake_timeouts_total 11232
telemt_upstream_connect_attempt_total 23817
telemt_upstream_connect_success_total 23729
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 23729
telemt_upstream_connect_attempts_per_request{bucket="2"} 42
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9410
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 262
telemt_me_reconnect_attempts_total 5050
telemt_me_reconnect_success_total 5014
telemt_me_reader_eof_total 5186
telemt_me_idle_close_by_peer_total 5186
telemt_me_route_drop_no_conn_total 65588
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 139
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 526
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 350
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 196
telemt_desync_frames_bucket_total{bucket="gt_10"} 233
telemt_pool_swap_total 12
telemt_pool_force_close_total 287
telemt_me_writer_removed_unexpected_total 5187
telemt_me_writer_restored_same_endpoint_total 5006
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 169238
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 2312640964 (2.15 GB)
telemt_user_octets_to_client{user="hello"} 56689842384 (52.80 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 34882.5 (9h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 230063
telemt_connections_bad_total 3311
telemt_handshake_timeouts_total 1247
telemt_upstream_connect_attempt_total 23710
telemt_upstream_connect_success_total 23655
telemt_upstream_connect_attempts_per_request{bucket="1"} 23655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9591
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 366
telemt_me_reconnect_attempts_total 4373
telemt_me_reconnect_success_total 4352
telemt_me_reader_eof_total 4496
telemt_me_idle_close_by_peer_total 4495
telemt_me_route_drop_no_conn_total 95059
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 149
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 497
telemt_desync_full_logged_total 195
telemt_desync_suppressed_total 302
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 223
telemt_desync_frames_bucket_total{bucket="gt_10"} 171
telemt_pool_swap_total 10
telemt_pool_force_close_total 208
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 4511
telemt_me_writer_restored_same_endpoint_total 4345
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 220064
telemt_user_connections_current{user="hello"} 516
telemt_user_octets_from_client{user="hello"} 24939850632 (23.23 GB)
telemt_user_octets_to_client{user="hello"} 128833902820 (119.99 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 91
```