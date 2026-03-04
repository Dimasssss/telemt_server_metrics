# Server Metrics 2026-03-04 10:31:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 48022.6 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 707178
telemt_connections_bad_total 10953
telemt_handshake_timeouts_total 7791
telemt_upstream_connect_attempt_total 31154
telemt_upstream_connect_success_total 31026
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 31026
telemt_upstream_connect_attempts_per_request{bucket="2"} 54
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13831
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 337
telemt_me_reconnect_attempts_total 7049
telemt_me_reconnect_success_total 7005
telemt_me_reader_eof_total 7224
telemt_me_idle_close_by_peer_total 7224
telemt_me_route_drop_no_conn_total 272443
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 191
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1231
telemt_desync_full_logged_total 425
telemt_desync_suppressed_total 806
telemt_desync_frames_bucket_total{bucket="1_2"} 337
telemt_desync_frames_bucket_total{bucket="3_10"} 473
telemt_desync_frames_bucket_total{bucket="gt_10"} 421
telemt_pool_swap_total 11
telemt_pool_force_close_total 451
telemt_me_writer_removed_unexpected_total 7224
telemt_me_writer_restored_same_endpoint_total 6984
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 587039
telemt_user_connections_current{user="hello"} 1058
telemt_user_octets_from_client{user="hello"} 6483213328 (6.04 GB)
telemt_user_octets_to_client{user="hello"} 178262928736 (166.02 GB)
telemt_user_unique_ips_current{user="hello"} 103
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 48018.9 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 283218
telemt_connections_bad_total 2580
telemt_handshake_timeouts_total 26712
telemt_upstream_connect_attempt_total 94679
telemt_upstream_connect_success_total 93297
telemt_upstream_connect_fail_total 652
telemt_upstream_connect_attempts_per_request{bucket="1"} 93291
telemt_upstream_connect_attempts_per_request{bucket="2"} 658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 652
telemt_me_keepalive_timeout_total 1354
telemt_me_reconnect_attempts_total 54365
telemt_me_reconnect_success_total 54281
telemt_me_reader_eof_total 55681
telemt_me_idle_close_by_peer_total 55680
telemt_me_route_drop_no_conn_total 127279
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 202
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 573
telemt_desync_full_logged_total 203
telemt_desync_suppressed_total 370
telemt_desync_frames_bucket_total{bucket="1_2"} 112
telemt_desync_frames_bucket_total{bucket="3_10"} 251
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 3
telemt_pool_force_close_total 216
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 55761
telemt_me_writer_restored_same_endpoint_total 54256
telemt_me_writer_removed_unexpected_minus_restored_total 1505
telemt_user_connections_total{user="hello"} 219699
telemt_user_connections_current{user="hello"} 405
telemt_user_octets_from_client{user="hello"} 2638655792 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 73701920644 (68.64 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 48017.8 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 565505
telemt_connections_bad_total 145750
telemt_handshake_timeouts_total 17260
telemt_upstream_connect_attempt_total 70415
telemt_upstream_connect_success_total 69984
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 69983
telemt_upstream_connect_attempts_per_request{bucket="2"} 207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28959
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 196
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_timeout_total 921
telemt_me_reconnect_attempts_total 32333
telemt_me_reconnect_success_total 32249
telemt_me_reader_eof_total 34000
telemt_me_idle_close_by_peer_total 33996
telemt_me_route_drop_no_conn_total 202303
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 202
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 943
telemt_desync_full_logged_total 342
telemt_desync_suppressed_total 601
telemt_desync_frames_bucket_total{bucket="1_2"} 283
telemt_desync_frames_bucket_total{bucket="3_10"} 316
telemt_desync_frames_bucket_total{bucket="gt_10"} 344
telemt_pool_swap_total 4
telemt_pool_force_close_total 201
telemt_me_writer_removed_unexpected_total 34011
telemt_me_writer_restored_same_endpoint_total 32228
telemt_me_writer_removed_unexpected_minus_restored_total 1783
telemt_user_connections_total{user="hello"} 384343
telemt_user_connections_current{user="hello"} 581
telemt_user_octets_from_client{user="hello"} 4604552628 (4.29 GB)
telemt_user_octets_to_client{user="hello"} 133697880296 (124.52 GB)
telemt_user_unique_ips_current{user="hello"} 67
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 48016.7 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371653
telemt_connections_bad_total 25335
telemt_handshake_timeouts_total 65842
telemt_upstream_connect_attempt_total 34560
telemt_upstream_connect_success_total 34419
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 34419
telemt_upstream_connect_attempts_per_request{bucket="2"} 69
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13006
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 384
telemt_me_reconnect_attempts_total 6920
telemt_me_reconnect_success_total 6896
telemt_me_reader_eof_total 7033
telemt_me_idle_close_by_peer_total 7033
telemt_me_route_drop_no_conn_total 103235
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 199
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 201
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 119
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 13
telemt_pool_force_close_total 316
telemt_me_writer_removed_unexpected_total 7033
telemt_me_writer_restored_same_endpoint_total 6875
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 258857
telemt_user_connections_current{user="hello"} 299
telemt_user_octets_from_client{user="hello"} 2801503392 (2.61 GB)
telemt_user_octets_to_client{user="hello"} 93891882308 (87.44 GB)
telemt_user_unique_ips_current{user="hello"} 32
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 48015.5 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 500655
telemt_connections_bad_total 6809
telemt_handshake_timeouts_total 132265
telemt_upstream_connect_attempt_total 69301
telemt_upstream_connect_success_total 68846
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 68846
telemt_upstream_connect_attempts_per_request{bucket="2"} 215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41353
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27302
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 907
telemt_me_reconnect_attempts_total 33644
telemt_me_reconnect_success_total 33612
telemt_me_reader_eof_total 35292
telemt_me_idle_close_by_peer_total 35291
telemt_me_route_drop_no_conn_total 156488
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 203
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 522
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 350
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 236
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 6
telemt_pool_force_close_total 262
telemt_pool_stale_pick_total 2870
telemt_me_writer_removed_unexpected_total 35304
telemt_me_writer_restored_same_endpoint_total 33587
telemt_me_writer_removed_unexpected_minus_restored_total 1717
telemt_user_connections_total{user="hello"} 340661
telemt_user_connections_current{user="hello"} 547
telemt_user_octets_from_client{user="hello"} 4580123384 (4.27 GB)
telemt_user_octets_to_client{user="hello"} 87832159828 (81.80 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 49
```