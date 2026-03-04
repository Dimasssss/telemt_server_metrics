# Server Metrics 2026-03-04 14:21:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 61858.1 (17h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1132650
telemt_connections_bad_total 13927
telemt_handshake_timeouts_total 20181
telemt_upstream_connect_attempt_total 37071
telemt_upstream_connect_success_total 36904
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 36904
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16522
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 425
telemt_me_reconnect_attempts_total 8165
telemt_me_reconnect_success_total 8106
telemt_me_reader_eof_total 8370
telemt_me_idle_close_by_peer_total 8369
telemt_me_route_drop_no_conn_total 419532
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 242
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2019
telemt_desync_full_logged_total 669
telemt_desync_suppressed_total 1350
telemt_desync_frames_bucket_total{bucket="1_2"} 591
telemt_desync_frames_bucket_total{bucket="3_10"} 768
telemt_desync_frames_bucket_total{bucket="gt_10"} 660
telemt_pool_swap_total 16
telemt_pool_force_close_total 682
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8370
telemt_me_writer_restored_same_endpoint_total 8084
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 902618
telemt_user_connections_current{user="hello"} 1155
telemt_user_octets_from_client{user="hello"} 11534394460 (10.74 GB)
telemt_user_octets_to_client{user="hello"} 303781447144 (282.92 GB)
telemt_user_unique_ips_current{user="hello"} 124
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 61854.5 (17h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 431406
telemt_connections_bad_total 3671
telemt_handshake_timeouts_total 29556
telemt_upstream_connect_attempt_total 111297
telemt_upstream_connect_success_total 109626
telemt_upstream_connect_fail_total 797
telemt_upstream_connect_attempts_per_request{bucket="1"} 109620
telemt_upstream_connect_attempts_per_request{bucket="2"} 803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71810
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 797
telemt_me_keepalive_timeout_total 1491
telemt_me_reconnect_attempts_total 60961
telemt_me_reconnect_success_total 60862
telemt_me_reader_eof_total 62465
telemt_me_idle_close_by_peer_total 62464
telemt_me_route_drop_no_conn_total 175531
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 259
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 904
telemt_desync_full_logged_total 270
telemt_desync_suppressed_total 634
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 376
telemt_desync_frames_bucket_total{bucket="gt_10"} 357
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 62545
telemt_me_writer_restored_same_endpoint_total 60837
telemt_me_writer_removed_unexpected_minus_restored_total 1708
telemt_user_connections_total{user="hello"} 335785
telemt_user_connections_current{user="hello"} 401
telemt_user_octets_from_client{user="hello"} 4479716864 (4.17 GB)
telemt_user_octets_to_client{user="hello"} 106550159556 (99.23 GB)
telemt_user_unique_ips_current{user="hello"} 35
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 61853.3 (17h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 856720
telemt_connections_bad_total 183860
telemt_handshake_timeouts_total 29245
telemt_upstream_connect_attempt_total 83840
telemt_upstream_connect_success_total 83315
telemt_upstream_connect_fail_total 253
telemt_upstream_connect_attempts_per_request{bucket="1"} 83314
telemt_upstream_connect_attempts_per_request{bucket="2"} 254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33866
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 253
telemt_me_keepalive_timeout_total 1091
telemt_me_reconnect_attempts_total 37988
telemt_me_reconnect_success_total 37889
telemt_me_reader_eof_total 39886
telemt_me_idle_close_by_peer_total 39882
telemt_me_route_drop_no_conn_total 312612
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_single_endpoint_shadow_rotate_total 255
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1752
telemt_desync_full_logged_total 589
telemt_desync_suppressed_total 1163
telemt_desync_frames_bucket_total{bucket="1_2"} 569
telemt_desync_frames_bucket_total{bucket="3_10"} 565
telemt_desync_frames_bucket_total{bucket="gt_10"} 618
telemt_pool_swap_total 7
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 39898
telemt_me_writer_restored_same_endpoint_total 37867
telemt_me_writer_removed_unexpected_minus_restored_total 2031
telemt_user_connections_total{user="hello"} 604839
telemt_user_connections_current{user="hello"} 572
telemt_user_octets_from_client{user="hello"} 12589903212 (11.73 GB)
telemt_user_octets_to_client{user="hello"} 206078534064 (191.93 GB)
telemt_user_unique_ips_current{user="hello"} 65
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 8530.7 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111077
telemt_connections_bad_total 11748
telemt_handshake_timeouts_total 3791
telemt_upstream_connect_attempt_total 4517
telemt_upstream_connect_success_total 4517
telemt_upstream_connect_attempts_per_request{bucket="1"} 4517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1747
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 848
telemt_me_reconnect_success_total 860
telemt_me_reader_eof_total 867
telemt_me_idle_close_by_peer_total 867
telemt_me_route_drop_no_conn_total 41140
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 153
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 90
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 2
telemt_pool_force_close_total 93
telemt_me_writer_removed_unexpected_total 867
telemt_me_writer_restored_same_endpoint_total 839
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 93545
telemt_user_connections_current{user="hello"} 539
telemt_user_octets_from_client{user="hello"} 1516664428 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 53258409512 (49.60 GB)
telemt_user_unique_ips_current{user="hello"} 68
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 8890.1 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153786
telemt_connections_bad_total 1411
telemt_handshake_timeouts_total 2625
telemt_upstream_connect_attempt_total 5407
telemt_upstream_connect_success_total 5380
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 5380
telemt_upstream_connect_attempts_per_request{bucket="2"} 13
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3145
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2226
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 77
telemt_me_reconnect_attempts_total 1216
telemt_me_reconnect_success_total 1225
telemt_me_reader_eof_total 1248
telemt_me_idle_close_by_peer_total 1248
telemt_me_route_drop_no_conn_total 53972
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 426
telemt_desync_full_logged_total 157
telemt_desync_suppressed_total 269
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 181
telemt_desync_frames_bucket_total{bucket="gt_10"} 192
telemt_pool_swap_total 1
telemt_pool_force_close_total 53
telemt_me_writer_removed_unexpected_total 1248
telemt_me_writer_restored_same_endpoint_total 1205
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 132126
telemt_user_connections_current{user="hello"} 567
telemt_user_octets_from_client{user="hello"} 1495223920 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 37018673048 (34.48 GB)
telemt_user_unique_ips_current{user="hello"} 57
```