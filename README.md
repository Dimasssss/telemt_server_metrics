# Server Metrics 2026-03-05 00:12:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 11926.9 (3h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100842
telemt_connections_bad_total 1399
telemt_handshake_timeouts_total 753
telemt_upstream_connect_attempt_total 15794
telemt_upstream_connect_success_total 15630
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 15629
telemt_upstream_connect_attempts_per_request{bucket="2"} 52
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5480
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 526
telemt_me_reconnect_attempts_total 7179
telemt_me_reconnect_success_total 7172
telemt_me_reader_eof_total 7418
telemt_me_idle_close_by_peer_total 7417
telemt_me_route_drop_no_conn_total 27020
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 130
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_me_writer_removed_unexpected_total 7477
telemt_me_writer_restored_same_endpoint_total 7152
telemt_me_writer_removed_unexpected_minus_restored_total 325
telemt_user_connections_total{user="hello"} 87779
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 2868232036 (2.67 GB)
telemt_user_octets_to_client{user="hello"} 48852304096 (45.50 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 11921.9 (3h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39265
telemt_connections_bad_total 760
telemt_handshake_timeouts_total 766
telemt_upstream_connect_attempt_total 12549
telemt_upstream_connect_success_total 12249
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 12239
telemt_upstream_connect_attempts_per_request{bucket="2"} 62
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4053
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 1014
telemt_me_reconnect_attempts_total 4748
telemt_me_reconnect_success_total 4722
telemt_me_reader_eof_total 4783
telemt_me_idle_close_by_peer_total 4782
telemt_me_route_drop_no_conn_total 12003
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 138
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_removed_unexpected_total 4887
telemt_me_writer_restored_same_endpoint_total 4697
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 35565
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 307207724 (292.98 MB)
telemt_user_octets_to_client{user="hello"} 10182100472 (9.48 GB)
telemt_user_unique_ips_current{user="hello"} 15
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 11918.4 (3h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91500
telemt_connections_bad_total 1304
telemt_handshake_timeouts_total 677
telemt_upstream_connect_attempt_total 5009
telemt_upstream_connect_success_total 4955
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 4955
telemt_upstream_connect_attempts_per_request{bucket="2"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2336
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 48
telemt_me_reconnect_attempts_total 258
telemt_me_reconnect_success_total 268
telemt_me_reader_eof_total 257
telemt_me_idle_close_by_peer_total 257
telemt_me_route_drop_no_conn_total 26198
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 172
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_pool_swap_total 4
telemt_pool_force_close_total 98
telemt_me_writer_removed_unexpected_total 257
telemt_me_writer_restored_same_endpoint_total 248
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 83880
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 1032018352 (984.21 MB)
telemt_user_octets_to_client{user="hello"} 28138708072 (26.21 GB)
telemt_user_unique_ips_current{user="hello"} 31
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 43966.7 (12h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 548730
telemt_connections_bad_total 79179
telemt_handshake_timeouts_total 14728
telemt_upstream_connect_attempt_total 19604
telemt_upstream_connect_success_total 19602
telemt_upstream_connect_attempts_per_request{bucket="1"} 19602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11294
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8304
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 248
telemt_me_reconnect_attempts_total 2616
telemt_me_reconnect_success_total 2599
telemt_me_reader_eof_total 2651
telemt_me_idle_close_by_peer_total 2651
telemt_me_route_drop_no_conn_total 185286
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 178
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 720
telemt_desync_full_logged_total 303
telemt_desync_suppressed_total 417
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 291
telemt_pool_swap_total 17
telemt_pool_force_close_total 484
telemt_pool_stale_pick_total 22
telemt_me_writer_removed_unexpected_total 2652
telemt_me_writer_restored_same_endpoint_total 2572
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 426327
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 5831606812 (5.43 GB)
telemt_user_octets_to_client{user="hello"} 159416809376 (148.47 GB)
telemt_user_unique_ips_current{user="hello"} 19
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 44325.9 (12h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 535443
telemt_connections_bad_total 3841
telemt_handshake_timeouts_total 5897
telemt_upstream_connect_attempt_total 28794
telemt_upstream_connect_success_total 28639
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 28639
telemt_upstream_connect_attempts_per_request{bucket="2"} 61
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11920
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 432
telemt_me_reconnect_attempts_total 6529
telemt_me_reconnect_success_total 6509
telemt_me_reader_eof_total 6753
telemt_me_idle_close_by_peer_total 6752
telemt_me_route_drop_no_conn_total 235858
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 180
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 828
telemt_desync_full_logged_total 301
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 350
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 10
telemt_pool_force_close_total 420
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 6758
telemt_me_writer_restored_same_endpoint_total 6487
telemt_me_writer_removed_unexpected_minus_restored_total 271
telemt_user_connections_total{user="hello"} 484942
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 7373978292 (6.87 GB)
telemt_user_octets_to_client{user="hello"} 162254344020 (151.11 GB)
telemt_user_unique_ips_current{user="hello"} 32
```