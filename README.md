# Server Metrics 2026-03-03 23:30:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 8370.4 (2h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65882
telemt_connections_bad_total 647
telemt_handshake_timeouts_total 211
telemt_upstream_connect_attempt_total 5098
telemt_upstream_connect_success_total 5071
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 5071
telemt_upstream_connect_attempts_per_request{bucket="2"} 10
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2216
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 57
telemt_me_reconnect_attempts_total 699
telemt_me_reconnect_success_total 709
telemt_me_reader_eof_total 700
telemt_me_idle_close_by_peer_total 700
telemt_me_route_drop_no_conn_total 26146
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 110
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 1
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 700
telemt_me_writer_restored_same_endpoint_total 689
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 63692
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 539786876 (514.78 MB)
telemt_user_octets_to_client{user="hello"} 20127580992 (18.75 GB)
telemt_user_unique_ips_current{user="hello"} 52
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 8367.1 (2h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30962
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 6279
telemt_upstream_connect_attempt_total 11877
telemt_upstream_connect_success_total 11690
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 11690
telemt_upstream_connect_attempts_per_request{bucket="2"} 91
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7512
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4176
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 5319
telemt_me_reconnect_success_total 5330
telemt_me_reader_eof_total 5406
telemt_me_idle_close_by_peer_total 5405
telemt_me_route_drop_no_conn_total 11845
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 76
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_me_writer_removed_unexpected_total 5406
telemt_me_writer_restored_same_endpoint_total 5310
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 24274
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 154412624 (147.26 MB)
telemt_user_octets_to_client{user="hello"} 13133900980 (12.23 GB)
telemt_user_unique_ips_current{user="hello"} 15
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 8365.8 (2h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71896
telemt_connections_bad_total 20268
telemt_handshake_timeouts_total 1771
telemt_upstream_connect_attempt_total 10328
telemt_upstream_connect_success_total 10276
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 10276
telemt_upstream_connect_attempts_per_request{bucket="2"} 23
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4312
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 125
telemt_me_reconnect_attempts_total 3997
telemt_me_reconnect_success_total 4002
telemt_me_reader_eof_total 4175
telemt_me_idle_close_by_peer_total 4174
telemt_me_route_drop_no_conn_total 15867
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 153
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 1
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 4176
telemt_me_writer_restored_same_endpoint_total 3981
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 48686
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 319579592 (304.77 MB)
telemt_user_octets_to_client{user="hello"} 13688380208 (12.75 GB)
telemt_user_unique_ips_current{user="hello"} 23
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 8364.8 (2h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32940
telemt_connections_bad_total 107
telemt_handshake_timeouts_total 485
telemt_upstream_connect_attempt_total 4632
telemt_upstream_connect_success_total 4609
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 4609
telemt_upstream_connect_attempts_per_request{bucket="2"} 11
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1793
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 412
telemt_me_reconnect_success_total 426
telemt_me_reader_eof_total 410
telemt_me_idle_close_by_peer_total 410
telemt_me_route_drop_no_conn_total 12619
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 2
telemt_pool_force_close_total 67
telemt_me_writer_removed_unexpected_total 410
telemt_me_writer_restored_same_endpoint_total 407
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 31898
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 233893148 (223.06 MB)
telemt_user_octets_to_client{user="hello"} 9661365280 (9.00 GB)
telemt_user_unique_ips_current{user="hello"} 29
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 8363.3 (2h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76578
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 29986
telemt_upstream_connect_attempt_total 6367
telemt_upstream_connect_success_total 6293
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 6293
telemt_upstream_connect_attempts_per_request{bucket="2"} 34
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2476
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 1694
telemt_me_reconnect_success_total 1709
telemt_me_reader_eof_total 1752
telemt_me_idle_close_by_peer_total 1752
telemt_me_route_drop_no_conn_total 32464
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 39
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 1754
telemt_me_writer_restored_same_endpoint_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 45210
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 223484544 (213.13 MB)
telemt_user_octets_to_client{user="hello"} 12431714536 (11.58 GB)
telemt_user_unique_ips_current{user="hello"} 23
```