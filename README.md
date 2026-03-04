# Server Metrics 2026-03-04 01:17:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 14820.6 (4h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100181
telemt_connections_bad_total 1318
telemt_handshake_timeouts_total 520
telemt_upstream_connect_attempt_total 11476
telemt_upstream_connect_success_total 11425
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 11425
telemt_upstream_connect_attempts_per_request{bucket="2"} 21
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6384
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5021
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 2905
telemt_me_reconnect_success_total 2907
telemt_me_reader_eof_total 2969
telemt_me_idle_close_by_peer_total 2969
telemt_me_route_drop_no_conn_total 37505
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 62
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 145
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 96
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 2
telemt_pool_force_close_total 78
telemt_me_writer_removed_unexpected_total 2969
telemt_me_writer_restored_same_endpoint_total 2887
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 96032
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 726689924 (693.03 MB)
telemt_user_octets_to_client{user="hello"} 29396951428 (27.38 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 14817.3 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46747
telemt_connections_bad_total 104
telemt_handshake_timeouts_total 11544
telemt_upstream_connect_attempt_total 30283
telemt_upstream_connect_success_total 29913
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 29907
telemt_upstream_connect_attempts_per_request{bucket="2"} 175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9553
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_keepalive_timeout_total 660
telemt_me_reconnect_attempts_total 17298
telemt_me_reconnect_success_total 17288
telemt_me_reader_eof_total 17724
telemt_me_idle_close_by_peer_total 17723
telemt_me_route_drop_no_conn_total 16693
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 65
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 79
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_me_writer_removed_unexpected_total 17785
telemt_me_writer_restored_same_endpoint_total 17268
telemt_me_writer_removed_unexpected_minus_restored_total 517
telemt_user_connections_total{user="hello"} 34578
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 243812256 (232.52 MB)
telemt_user_octets_to_client{user="hello"} 20368065780 (18.97 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 14816.2 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108897
telemt_connections_bad_total 37154
telemt_handshake_timeouts_total 1971
telemt_upstream_connect_attempt_total 16632
telemt_upstream_connect_success_total 16527
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 16527
telemt_upstream_connect_attempts_per_request{bucket="2"} 48
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6855
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 208
telemt_me_reconnect_attempts_total 5720
telemt_me_reconnect_success_total 5714
telemt_me_reader_eof_total 5950
telemt_me_idle_close_by_peer_total 5948
telemt_me_route_drop_no_conn_total 21195
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 65
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 230
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 155
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 97
telemt_pool_swap_total 2
telemt_pool_force_close_total 61
telemt_me_writer_removed_unexpected_total 5951
telemt_me_writer_restored_same_endpoint_total 5693
telemt_me_writer_removed_unexpected_minus_restored_total 258
telemt_user_connections_total{user="hello"} 68420
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 424089476 (404.44 MB)
telemt_user_octets_to_client{user="hello"} 17550414564 (16.35 GB)
telemt_user_unique_ips_current{user="hello"} 21
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 14814.9 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48707
telemt_connections_bad_total 170
telemt_handshake_timeouts_total 531
telemt_upstream_connect_attempt_total 9490
telemt_upstream_connect_success_total 9451
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 9451
telemt_upstream_connect_attempts_per_request{bucket="2"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1347
telemt_me_reconnect_success_total 1357
telemt_me_reader_eof_total 1358
telemt_me_idle_close_by_peer_total 1358
telemt_me_route_drop_no_conn_total 16618
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 16
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 4
telemt_pool_force_close_total 101
telemt_me_writer_removed_unexpected_total 1358
telemt_me_writer_restored_same_endpoint_total 1337
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 47184
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 410701060 (391.68 MB)
telemt_user_octets_to_client{user="hello"} 12647447084 (11.78 GB)
telemt_user_unique_ips_current{user="hello"} 31
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 14813.6 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117708
telemt_connections_bad_total 52
telemt_handshake_timeouts_total 51211
telemt_upstream_connect_attempt_total 22768
telemt_upstream_connect_success_total 22635
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 22635
telemt_upstream_connect_attempts_per_request{bucket="2"} 63
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9696
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 302
telemt_me_reconnect_attempts_total 11944
telemt_me_reconnect_success_total 11944
telemt_me_reader_eof_total 12718
telemt_me_idle_close_by_peer_total 12717
telemt_me_route_drop_no_conn_total 37548
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 66
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 90
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 12723
telemt_me_writer_restored_same_endpoint_total 11920
telemt_me_writer_removed_unexpected_minus_restored_total 803
telemt_user_connections_total{user="hello"} 64247
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 310508456 (296.12 MB)
telemt_user_octets_to_client{user="hello"} 15426435412 (14.37 GB)
telemt_user_unique_ips_current{user="hello"} 10
```