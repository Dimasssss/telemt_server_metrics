# Server Metrics 2026-03-04 10:41:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 48637.0 (13h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 728821
telemt_connections_bad_total 11055
telemt_handshake_timeouts_total 8434
telemt_upstream_connect_attempt_total 31367
telemt_upstream_connect_success_total 31239
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 31239
telemt_upstream_connect_attempts_per_request{bucket="2"} 54
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13917
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 341
telemt_me_reconnect_attempts_total 7051
telemt_me_reconnect_success_total 7007
telemt_me_reader_eof_total 7226
telemt_me_idle_close_by_peer_total 7226
telemt_me_route_drop_no_conn_total 284638
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 191
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1235
telemt_desync_full_logged_total 427
telemt_desync_suppressed_total 808
telemt_desync_frames_bucket_total{bucket="1_2"} 339
telemt_desync_frames_bucket_total{bucket="3_10"} 475
telemt_desync_frames_bucket_total{bucket="gt_10"} 421
telemt_pool_swap_total 11
telemt_pool_force_close_total 451
telemt_me_writer_removed_unexpected_total 7226
telemt_me_writer_restored_same_endpoint_total 6986
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 603011
telemt_user_connections_current{user="hello"} 1036
telemt_user_octets_from_client{user="hello"} 6709330212 (6.25 GB)
telemt_user_octets_to_client{user="hello"} 181623881888 (169.15 GB)
telemt_user_unique_ips_current{user="hello"} 108
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 48633.4 (13h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 289609
telemt_connections_bad_total 2737
telemt_handshake_timeouts_total 26863
telemt_upstream_connect_attempt_total 95106
telemt_upstream_connect_success_total 93722
telemt_upstream_connect_fail_total 654
telemt_upstream_connect_attempts_per_request{bucket="1"} 93716
telemt_upstream_connect_attempts_per_request{bucket="2"} 660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30867
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 654
telemt_me_keepalive_timeout_total 1358
telemt_me_reconnect_attempts_total 54421
telemt_me_reconnect_success_total 54337
telemt_me_reader_eof_total 55737
telemt_me_idle_close_by_peer_total 55736
telemt_me_route_drop_no_conn_total 129812
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 205
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 577
telemt_desync_full_logged_total 204
telemt_desync_suppressed_total 373
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 254
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 3
telemt_pool_force_close_total 216
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 55817
telemt_me_writer_restored_same_endpoint_total 54312
telemt_me_writer_removed_unexpected_minus_restored_total 1505
telemt_user_connections_total{user="hello"} 225665
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 2679653812 (2.50 GB)
telemt_user_octets_to_client{user="hello"} 75462850868 (70.28 GB)
telemt_user_unique_ips_current{user="hello"} 39
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 48632.3 (13h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 577322
telemt_connections_bad_total 147339
telemt_handshake_timeouts_total 17675
telemt_upstream_connect_attempt_total 71754
telemt_upstream_connect_success_total 71323
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 71322
telemt_upstream_connect_attempts_per_request{bucket="2"} 207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29443
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 202
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_timeout_total 930
telemt_me_reconnect_attempts_total 33120
telemt_me_reconnect_success_total 33035
telemt_me_reader_eof_total 34820
telemt_me_idle_close_by_peer_total 34816
telemt_me_route_drop_no_conn_total 208394
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 202
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 975
telemt_desync_full_logged_total 352
telemt_desync_suppressed_total 623
telemt_desync_frames_bucket_total{bucket="1_2"} 293
telemt_desync_frames_bucket_total{bucket="3_10"} 327
telemt_desync_frames_bucket_total{bucket="gt_10"} 355
telemt_pool_swap_total 4
telemt_pool_force_close_total 201
telemt_me_writer_removed_unexpected_total 34832
telemt_me_writer_restored_same_endpoint_total 33014
telemt_me_writer_removed_unexpected_minus_restored_total 1818
telemt_user_connections_total{user="hello"} 393818
telemt_user_connections_current{user="hello"} 584
telemt_user_octets_from_client{user="hello"} 4799842472 (4.47 GB)
telemt_user_octets_to_client{user="hello"} 136042420472 (126.70 GB)
telemt_user_unique_ips_current{user="hello"} 61
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 48631.2 (13h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 378095
telemt_connections_bad_total 25879
telemt_handshake_timeouts_total 66041
telemt_upstream_connect_attempt_total 35194
telemt_upstream_connect_success_total 35053
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 35053
telemt_upstream_connect_attempts_per_request{bucket="2"} 69
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13272
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 394
telemt_me_reconnect_attempts_total 7083
telemt_me_reconnect_success_total 7058
telemt_me_reader_eof_total 7200
telemt_me_idle_close_by_peer_total 7200
telemt_me_route_drop_no_conn_total 105516
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 199
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 204
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 13
telemt_pool_force_close_total 316
telemt_me_writer_removed_unexpected_total 7200
telemt_me_writer_restored_same_endpoint_total 7037
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 264459
telemt_user_connections_current{user="hello"} 379
telemt_user_octets_from_client{user="hello"} 2864739120 (2.67 GB)
telemt_user_octets_to_client{user="hello"} 95549296668 (88.99 GB)
telemt_user_unique_ips_current{user="hello"} 39
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 48629.9 (13h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 510971
telemt_connections_bad_total 6809
telemt_handshake_timeouts_total 132337
telemt_upstream_connect_attempt_total 69748
telemt_upstream_connect_success_total 69292
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 69292
telemt_upstream_connect_attempts_per_request{bucket="2"} 215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27427
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 913
telemt_me_reconnect_attempts_total 33797
telemt_me_reconnect_success_total 33765
telemt_me_reader_eof_total 35448
telemt_me_idle_close_by_peer_total 35447
telemt_me_route_drop_no_conn_total 159657
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 203
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 567
telemt_desync_full_logged_total 188
telemt_desync_suppressed_total 379
telemt_desync_frames_bucket_total{bucket="1_2"} 115
telemt_desync_frames_bucket_total{bucket="3_10"} 256
telemt_desync_frames_bucket_total{bucket="gt_10"} 196
telemt_pool_swap_total 6
telemt_pool_force_close_total 262
telemt_pool_stale_pick_total 2870
telemt_me_writer_removed_unexpected_total 35460
telemt_me_writer_restored_same_endpoint_total 33740
telemt_me_writer_removed_unexpected_minus_restored_total 1720
telemt_user_connections_total{user="hello"} 349688
telemt_user_connections_current{user="hello"} 614
telemt_user_octets_from_client{user="hello"} 4684203464 (4.36 GB)
telemt_user_octets_to_client{user="hello"} 92611869944 (86.25 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 53
```