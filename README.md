# Server Metrics 2026-03-07 00:39:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 23513.0 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300316
telemt_connections_bad_total 3033
telemt_handshake_timeouts_total 9394
telemt_upstream_connect_attempt_total 65853
telemt_upstream_connect_success_total 64124
telemt_upstream_connect_fail_total 1592
telemt_upstream_connect_attempts_per_request{bucket="1"} 65716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40625
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 89
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1592
telemt_me_keepalive_timeout_total 1605
telemt_me_reconnect_attempts_total 37181
telemt_me_reconnect_success_total 35644
telemt_me_reader_eof_total 38557
telemt_me_idle_close_by_peer_total 38557
telemt_me_route_drop_no_conn_total 115634
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 195
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 999
telemt_desync_full_logged_total 269
telemt_desync_suppressed_total 730
telemt_desync_frames_bucket_total{bucket="1_2"} 275
telemt_desync_frames_bucket_total{bucket="3_10"} 449
telemt_desync_frames_bucket_total{bucket="gt_10"} 275
telemt_pool_swap_total 10
telemt_pool_force_close_total 474
telemt_pool_stale_pick_total 187
telemt_me_writer_removed_unexpected_total 38670
telemt_me_writer_restored_same_endpoint_total 35546
telemt_me_writer_restored_fallback_total 92
telemt_me_async_recovery_trigger_total 29658
telemt_me_writer_removed_unexpected_minus_restored_total 3032
telemt_user_connections_total{user="hello"} 273016
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 4216559676 (3.93 GB)
telemt_user_octets_to_client{user="hello"} 120016835620 (111.77 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 23512.9 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128198
telemt_connections_bad_total 115
telemt_handshake_timeouts_total 15068
telemt_upstream_connect_attempt_total 126661
telemt_upstream_connect_success_total 126658
telemt_upstream_connect_attempts_per_request{bucket="1"} 126658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 91238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 1137
telemt_me_reconnect_attempts_total 93579
telemt_me_reconnect_success_total 93309
telemt_me_reader_eof_total 86397
telemt_me_idle_close_by_peer_total 86392
telemt_me_route_drop_no_conn_total 41659
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 204
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 808
telemt_desync_full_logged_total 213
telemt_desync_suppressed_total 595
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 406
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 16
telemt_pool_force_close_total 959
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 86426
telemt_me_writer_restored_same_endpoint_total 93307
telemt_me_async_recovery_trigger_total 29651
telemt_user_connections_total{user="hello"} 106709
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 1555345632 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 37402349988 (34.83 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 23512.9 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 232241
telemt_connections_bad_total 1228
telemt_handshake_timeouts_total 3573
telemt_upstream_connect_attempt_total 98424
telemt_upstream_connect_success_total 98249
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 98312
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33616
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 2040
telemt_me_reconnect_attempts_total 69652
telemt_me_reconnect_success_total 69589
telemt_me_reader_eof_total 71813
telemt_me_idle_close_by_peer_total 71808
telemt_me_route_drop_no_conn_total 88018
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 192
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1038
telemt_desync_full_logged_total 264
telemt_desync_suppressed_total 774
telemt_desync_frames_bucket_total{bucket="1_2"} 195
telemt_desync_frames_bucket_total{bucket="3_10"} 426
telemt_desync_frames_bucket_total{bucket="gt_10"} 417
telemt_pool_swap_total 12
telemt_pool_force_close_total 350
telemt_pool_stale_pick_total 126
telemt_me_writer_removed_unexpected_total 71981
telemt_me_writer_restored_same_endpoint_total 69582
telemt_me_async_recovery_trigger_total 88754
telemt_me_writer_removed_unexpected_minus_restored_total 2399
telemt_user_connections_total{user="hello"} 216674
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 19282318116 (17.96 GB)
telemt_user_octets_to_client{user="hello"} 62009111120 (57.75 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 23513.2 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 234738
telemt_connections_bad_total 65641
telemt_handshake_timeouts_total 16660
telemt_upstream_connect_attempt_total 42372
telemt_upstream_connect_success_total 42287
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 42325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 827
telemt_me_reconnect_attempts_total 13759
telemt_me_reconnect_success_total 13733
telemt_me_reader_eof_total 18731
telemt_me_idle_close_by_peer_total 18729
telemt_me_route_drop_no_conn_total 63100
telemt_me_single_endpoint_shadow_rotate_total 200
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 207
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 118
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 13
telemt_pool_force_close_total 418
telemt_pool_stale_pick_total 468
telemt_me_writer_removed_unexpected_total 18736
telemt_me_writer_restored_same_endpoint_total 13728
telemt_me_writer_removed_unexpected_minus_restored_total 5008
telemt_user_connections_total{user="hello"} 148494
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 1719786052 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 48665195100 (45.32 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 23511.6 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203223
telemt_connections_bad_total 504
telemt_handshake_timeouts_total 2302
telemt_upstream_connect_attempt_total 37758
telemt_upstream_connect_success_total 37608
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 37627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22476
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 232
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 1080
telemt_me_reconnect_attempts_total 10712
telemt_me_reconnect_success_total 10678
telemt_me_reader_eof_total 14462
telemt_me_idle_close_by_peer_total 14460
telemt_me_route_drop_no_conn_total 68135
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 191
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 773
telemt_desync_full_logged_total 200
telemt_desync_suppressed_total 573
telemt_desync_frames_bucket_total{bucket="1_2"} 267
telemt_desync_frames_bucket_total{bucket="3_10"} 251
telemt_desync_frames_bucket_total{bucket="gt_10"} 255
telemt_pool_swap_total 14
telemt_pool_force_close_total 428
telemt_pool_stale_pick_total 215
telemt_me_writer_removed_unexpected_total 14529
telemt_me_writer_restored_same_endpoint_total 10674
telemt_me_writer_removed_unexpected_minus_restored_total 3855
telemt_user_connections_total{user="hello"} 186619
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 10129671720 (9.43 GB)
telemt_user_octets_to_client{user="hello"} 65426593256 (60.93 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 25
```