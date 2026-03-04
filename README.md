# Server Metrics 2026-03-04 23:51:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 10697.9 (2h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94948
telemt_connections_bad_total 1395
telemt_handshake_timeouts_total 669
telemt_upstream_connect_attempt_total 13146
telemt_upstream_connect_success_total 12998
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 12997
telemt_upstream_connect_attempts_per_request{bucket="2"} 45
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4484
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 507
telemt_me_reconnect_attempts_total 5719
telemt_me_reconnect_success_total 5714
telemt_me_reader_eof_total 5894
telemt_me_idle_close_by_peer_total 5893
telemt_me_route_drop_no_conn_total 25504
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 130
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_me_writer_removed_unexpected_total 5953
telemt_me_writer_restored_same_endpoint_total 5694
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 82062
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 2814565868 (2.62 GB)
telemt_user_octets_to_client{user="hello"} 47198062804 (43.96 GB)
telemt_user_unique_ips_current{user="hello"} 26
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 10692.7 (2h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36391
telemt_connections_bad_total 757
telemt_handshake_timeouts_total 275
telemt_upstream_connect_attempt_total 11297
telemt_upstream_connect_success_total 11021
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 11012
telemt_upstream_connect_attempts_per_request{bucket="2"} 54
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3697
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 879
telemt_me_reconnect_attempts_total 4333
telemt_me_reconnect_success_total 4308
telemt_me_reader_eof_total 4370
telemt_me_idle_close_by_peer_total 4369
telemt_me_route_drop_no_conn_total 11250
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 138
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_removed_unexpected_total 4468
telemt_me_writer_restored_same_endpoint_total 4287
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 33246
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 285518960 (272.29 MB)
telemt_user_octets_to_client{user="hello"} 9604036228 (8.94 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 10689.4 (2h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84742
telemt_connections_bad_total 1287
telemt_handshake_timeouts_total 607
telemt_upstream_connect_attempt_total 4458
telemt_upstream_connect_success_total 4416
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 4416
telemt_upstream_connect_attempts_per_request{bucket="2"} 13
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2085
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 250
telemt_me_reconnect_success_total 262
telemt_me_reader_eof_total 251
telemt_me_idle_close_by_peer_total 251
telemt_me_route_drop_no_conn_total 24762
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 168
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 119
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 4
telemt_pool_force_close_total 98
telemt_me_writer_removed_unexpected_total 251
telemt_me_writer_restored_same_endpoint_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 78378
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 1009756064 (962.98 MB)
telemt_user_octets_to_client{user="hello"} 26111413496 (24.32 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 42737.5 (11h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 542986
telemt_connections_bad_total 77125
telemt_handshake_timeouts_total 14710
telemt_upstream_connect_attempt_total 18307
telemt_upstream_connect_success_total 18305
telemt_upstream_connect_attempts_per_request{bucket="1"} 18305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7797
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 234
telemt_me_reconnect_attempts_total 2297
telemt_me_reconnect_success_total 2280
telemt_me_reader_eof_total 2322
telemt_me_idle_close_by_peer_total 2322
telemt_me_route_drop_no_conn_total 183673
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 174
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
telemt_me_writer_removed_unexpected_total 2323
telemt_me_writer_restored_same_endpoint_total 2253
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 422716
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 5793174284 (5.40 GB)
telemt_user_octets_to_client{user="hello"} 157754968420 (146.92 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 43096.8 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 532349
telemt_connections_bad_total 3824
telemt_handshake_timeouts_total 5830
telemt_upstream_connect_attempt_total 27768
telemt_upstream_connect_success_total 27619
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 27619
telemt_upstream_connect_attempts_per_request{bucket="2"} 58
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11467
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 424
telemt_me_reconnect_attempts_total 6399
telemt_me_reconnect_success_total 6380
telemt_me_reader_eof_total 6622
telemt_me_idle_close_by_peer_total 6621
telemt_me_route_drop_no_conn_total 234609
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 173
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 828
telemt_desync_full_logged_total 301
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 350
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 9
telemt_pool_force_close_total 409
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 6627
telemt_me_writer_restored_same_endpoint_total 6358
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 481999
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 7359307660 (6.85 GB)
telemt_user_octets_to_client{user="hello"} 160992247920 (149.94 GB)
telemt_user_unique_ips_current{user="hello"} 28
```