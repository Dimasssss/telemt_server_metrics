# Server Metrics 2026-03-03 23:09:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 7142.2 (1h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58565
telemt_connections_bad_total 642
telemt_handshake_timeouts_total 172
telemt_upstream_connect_attempt_total 3794
telemt_upstream_connect_success_total 3771
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 3771
telemt_upstream_connect_attempts_per_request{bucket="2"} 8
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1601
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 433
telemt_me_reconnect_success_total 444
telemt_me_reader_eof_total 430
telemt_me_idle_close_by_peer_total 430
telemt_me_route_drop_no_conn_total 22784
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 110
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 1
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 430
telemt_me_writer_restored_same_endpoint_total 424
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 56530
telemt_user_connections_current{user="hello"} 325
telemt_user_octets_from_client{user="hello"} 504129852 (480.78 MB)
telemt_user_octets_to_client{user="hello"} 18744773692 (17.46 GB)
telemt_user_unique_ips_current{user="hello"} 42
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 7138.8 (1h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27180
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 5430
telemt_upstream_connect_attempt_total 8993
telemt_upstream_connect_success_total 8820
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 8820
telemt_upstream_connect_attempts_per_request{bucket="2"} 84
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3147
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 80
telemt_me_reconnect_attempts_total 3663
telemt_me_reconnect_success_total 3674
telemt_me_reader_eof_total 3724
telemt_me_idle_close_by_peer_total 3723
telemt_me_route_drop_no_conn_total 10212
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 56
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_me_writer_removed_unexpected_total 3724
telemt_me_writer_restored_same_endpoint_total 3654
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 21383
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 127261044 (121.37 MB)
telemt_user_octets_to_client{user="hello"} 9495573656 (8.84 GB)
telemt_user_unique_ips_current{user="hello"} 23
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 7137.5 (1h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65784
telemt_connections_bad_total 19414
telemt_handshake_timeouts_total 1739
telemt_upstream_connect_attempt_total 7626
telemt_upstream_connect_success_total 7584
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 7584
telemt_upstream_connect_attempts_per_request{bucket="2"} 18
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3184
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 84
telemt_me_reconnect_attempts_total 2446
telemt_me_reconnect_success_total 2454
telemt_me_reader_eof_total 2544
telemt_me_idle_close_by_peer_total 2543
telemt_me_route_drop_no_conn_total 13886
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 133
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 88
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 2545
telemt_me_writer_restored_same_endpoint_total 2433
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 43496
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 299607560 (285.73 MB)
telemt_user_octets_to_client{user="hello"} 13013012500 (12.12 GB)
telemt_user_unique_ips_current{user="hello"} 17
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 7136.5 (1h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28894
telemt_connections_bad_total 69
telemt_handshake_timeouts_total 470
telemt_upstream_connect_attempt_total 3886
telemt_upstream_connect_success_total 3865
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3865
telemt_upstream_connect_attempts_per_request{bucket="2"} 10
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1534
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 341
telemt_me_reconnect_success_total 356
telemt_me_reader_eof_total 339
telemt_me_idle_close_by_peer_total 339
telemt_me_route_drop_no_conn_total 10983
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 2
telemt_pool_force_close_total 67
telemt_me_writer_removed_unexpected_total 339
telemt_me_writer_restored_same_endpoint_total 337
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 27967
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 216511832 (206.48 MB)
telemt_user_octets_to_client{user="hello"} 8924356084 (8.31 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 7135.3 (1h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65006
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 24077
telemt_upstream_connect_attempt_total 4494
telemt_upstream_connect_success_total 4442
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 4442
telemt_upstream_connect_attempts_per_request{bucket="2"} 24
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1639
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 973
telemt_me_reconnect_success_total 988
telemt_me_reader_eof_total 1000
telemt_me_idle_close_by_peer_total 1000
telemt_me_route_drop_no_conn_total 30473
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 34
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 1002
telemt_me_writer_restored_same_endpoint_total 964
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 39801
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 202663756 (193.28 MB)
telemt_user_octets_to_client{user="hello"} 10124211356 (9.43 GB)
telemt_user_unique_ips_current{user="hello"} 21
```