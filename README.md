# Server Metrics 2026-03-04 22:04:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 4244.3 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49871
telemt_connections_bad_total 128
telemt_handshake_timeouts_total 403
telemt_upstream_connect_attempt_total 2621
telemt_upstream_connect_success_total 2589
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2589
telemt_upstream_connect_attempts_per_request{bucket="2"} 11
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1013
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 36
telemt_me_reconnect_attempts_total 464
telemt_me_reconnect_success_total 478
telemt_me_reader_eof_total 470
telemt_me_idle_close_by_peer_total 470
telemt_me_route_drop_no_conn_total 11794
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 95
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 470
telemt_me_writer_restored_same_endpoint_total 458
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 42491
telemt_user_connections_current{user="hello"} 446
telemt_user_octets_from_client{user="hello"} 2141330812 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 18330710412 (17.07 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 4238.9 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18752
telemt_connections_bad_total 673
telemt_handshake_timeouts_total 115
telemt_upstream_connect_attempt_total 2754
telemt_upstream_connect_success_total 2722
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 2722
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 445
telemt_me_reconnect_success_total 456
telemt_me_reader_eof_total 449
telemt_me_idle_close_by_peer_total 449
telemt_me_route_drop_no_conn_total 5372
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 84
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_me_writer_removed_unexpected_total 449
telemt_me_writer_restored_same_endpoint_total 437
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 17349
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 165717572 (158.04 MB)
telemt_user_octets_to_client{user="hello"} 4819892764 (4.49 GB)
telemt_user_unique_ips_current{user="hello"} 19
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 4235.6 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42614
telemt_connections_bad_total 702
telemt_handshake_timeouts_total 211
telemt_upstream_connect_attempt_total 1267
telemt_upstream_connect_success_total 1251
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 1251
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 541
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 18
telemt_me_reconnect_success_total 33
telemt_me_reader_eof_total 14
telemt_me_idle_close_by_peer_total 14
telemt_me_route_drop_no_conn_total 12398
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 117
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 2
telemt_pool_force_close_total 51
telemt_me_writer_removed_unexpected_total 14
telemt_me_writer_restored_same_endpoint_total 13
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 38518
telemt_user_connections_current{user="hello"} 268
telemt_user_octets_from_client{user="hello"} 580804868 (553.90 MB)
telemt_user_octets_to_client{user="hello"} 15134400276 (14.10 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 36283.8 (10h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 505073
telemt_connections_bad_total 66215
telemt_handshake_timeouts_total 14638
telemt_upstream_connect_attempt_total 15851
telemt_upstream_connect_success_total 15851
telemt_upstream_connect_attempts_per_request{bucket="1"} 15851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6886
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 215
telemt_me_reconnect_attempts_total 2135
telemt_me_reconnect_success_total 2122
telemt_me_reader_eof_total 2162
telemt_me_idle_close_by_peer_total 2162
telemt_me_route_drop_no_conn_total 174605
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 147
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 695
telemt_desync_full_logged_total 292
telemt_desync_suppressed_total 403
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 196
telemt_desync_frames_bucket_total{bucket="gt_10"} 281
telemt_pool_swap_total 13
telemt_pool_force_close_total 423
telemt_me_writer_removed_unexpected_total 2163
telemt_me_writer_restored_same_endpoint_total 2098
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 396165
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 5625792656 (5.24 GB)
telemt_user_octets_to_client{user="hello"} 152606397992 (142.13 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 36643.0 (10h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 506636
telemt_connections_bad_total 3758
telemt_handshake_timeouts_total 5613
telemt_upstream_connect_attempt_total 21664
telemt_upstream_connect_success_total 21550
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 21550
telemt_upstream_connect_attempts_per_request{bucket="2"} 47
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9151
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 309
telemt_me_reconnect_attempts_total 4559
telemt_me_reconnect_success_total 4547
telemt_me_reader_eof_total 4711
telemt_me_idle_close_by_peer_total 4711
telemt_me_route_drop_no_conn_total 224687
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 148
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 825
telemt_desync_full_logged_total 298
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 166
telemt_desync_frames_bucket_total{bucket="3_10"} 349
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 8
telemt_pool_force_close_total 370
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 4714
telemt_me_writer_restored_same_endpoint_total 4526
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 457380
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 7108410956 (6.62 GB)
telemt_user_octets_to_client{user="hello"} 146259235532 (136.21 GB)
telemt_user_unique_ips_current{user="hello"} 28
```