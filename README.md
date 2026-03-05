# Server Metrics 2026-03-05 00:37:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 13462.9 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109153
telemt_connections_bad_total 1455
telemt_handshake_timeouts_total 811
telemt_upstream_connect_attempt_total 19628
telemt_upstream_connect_success_total 19459
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 19458
telemt_upstream_connect_attempts_per_request{bucket="2"} 54
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12418
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6938
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 580
telemt_me_reconnect_attempts_total 9561
telemt_me_reconnect_success_total 9552
telemt_me_reader_eof_total 9912
telemt_me_idle_close_by_peer_total 9911
telemt_me_route_drop_no_conn_total 29592
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 134
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 54
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 69
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 9971
telemt_me_writer_restored_same_endpoint_total 9532
telemt_me_writer_removed_unexpected_minus_restored_total 439
telemt_user_connections_total{user="hello"} 95256
telemt_user_connections_current{user="hello"} 393
telemt_user_octets_from_client{user="hello"} 2912470024 (2.71 GB)
telemt_user_octets_to_client{user="hello"} 51347989056 (47.82 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 13457.7 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42261
telemt_connections_bad_total 786
telemt_handshake_timeouts_total 1048
telemt_upstream_connect_attempt_total 14992
telemt_upstream_connect_success_total 14683
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 14673
telemt_upstream_connect_attempts_per_request{bucket="2"} 66
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4877
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 1030
telemt_me_reconnect_attempts_total 5777
telemt_me_reconnect_success_total 5750
telemt_me_reader_eof_total 5838
telemt_me_idle_close_by_peer_total 5837
telemt_me_route_drop_no_conn_total 13005
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 138
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_removed_unexpected_total 5942
telemt_me_writer_restored_same_endpoint_total 5725
telemt_me_writer_removed_unexpected_minus_restored_total 217
telemt_user_connections_total{user="hello"} 38120
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 336409068 (320.82 MB)
telemt_user_octets_to_client{user="hello"} 10373299652 (9.66 GB)
telemt_user_unique_ips_current{user="hello"} 15
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 13454.3 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98104
telemt_connections_bad_total 1392
telemt_handshake_timeouts_total 702
telemt_upstream_connect_attempt_total 6223
telemt_upstream_connect_success_total 6167
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 6167
telemt_upstream_connect_attempts_per_request{bucket="2"} 20
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2959
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 67
telemt_me_reconnect_attempts_total 330
telemt_me_reconnect_success_total 339
telemt_me_reader_eof_total 329
telemt_me_idle_close_by_peer_total 329
telemt_me_route_drop_no_conn_total 27767
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 173
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 4
telemt_pool_force_close_total 98
telemt_me_writer_removed_unexpected_total 329
telemt_me_writer_restored_same_endpoint_total 319
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 90159
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 1066088668 (1016.70 MB)
telemt_user_octets_to_client{user="hello"} 33061537076 (30.79 GB)
telemt_user_unique_ips_current{user="hello"} 22
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 45502.5 (12h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 555256
telemt_connections_bad_total 81766
telemt_handshake_timeouts_total 14741
telemt_upstream_connect_attempt_total 21343
telemt_upstream_connect_success_total 21341
telemt_upstream_connect_attempts_per_request{bucket="1"} 21341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8994
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 262
telemt_me_reconnect_attempts_total 3147
telemt_me_reconnect_success_total 3127
telemt_me_reader_eof_total 3187
telemt_me_idle_close_by_peer_total 3187
telemt_me_route_drop_no_conn_total 186507
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 184
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 724
telemt_desync_full_logged_total 304
telemt_desync_suppressed_total 420
telemt_desync_frames_bucket_total{bucket="1_2"} 225
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 292
telemt_pool_swap_total 18
telemt_pool_force_close_total 507
telemt_pool_stale_pick_total 22
telemt_me_writer_removed_unexpected_total 3188
telemt_me_writer_restored_same_endpoint_total 3100
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 430229
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 5857327536 (5.46 GB)
telemt_user_octets_to_client{user="hello"} 160068760460 (149.08 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 45861.9 (12h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 539150
telemt_connections_bad_total 3858
telemt_handshake_timeouts_total 5915
telemt_upstream_connect_attempt_total 29471
telemt_upstream_connect_success_total 29314
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 29314
telemt_upstream_connect_attempts_per_request{bucket="2"} 62
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 441
telemt_me_reconnect_attempts_total 6543
telemt_me_reconnect_success_total 6521
telemt_me_reader_eof_total 6766
telemt_me_idle_close_by_peer_total 6765
telemt_me_route_drop_no_conn_total 237173
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 184
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 842
telemt_desync_full_logged_total 304
telemt_desync_suppressed_total 538
telemt_desync_frames_bucket_total{bucket="1_2"} 170
telemt_desync_frames_bucket_total{bucket="3_10"} 354
telemt_desync_frames_bucket_total{bucket="gt_10"} 318
telemt_pool_swap_total 10
telemt_pool_force_close_total 420
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 6771
telemt_me_writer_restored_same_endpoint_total 6499
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 488580
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 7388501544 (6.88 GB)
telemt_user_octets_to_client{user="hello"} 163651338316 (152.41 GB)
telemt_user_unique_ips_current{user="hello"} 22
```