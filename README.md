# Server Metrics 2026-03-04 10:51:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 49251.4 (13h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 754385
telemt_connections_bad_total 11381
telemt_handshake_timeouts_total 9029
telemt_upstream_connect_attempt_total 31661
telemt_upstream_connect_success_total 31527
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 31527
telemt_upstream_connect_attempts_per_request{bucket="2"} 57
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14049
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 348
telemt_me_reconnect_attempts_total 7068
telemt_me_reconnect_success_total 7023
telemt_me_reader_eof_total 7242
telemt_me_idle_close_by_peer_total 7242
telemt_me_route_drop_no_conn_total 295717
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 195
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1266
telemt_desync_full_logged_total 433
telemt_desync_suppressed_total 833
telemt_desync_frames_bucket_total{bucket="1_2"} 349
telemt_desync_frames_bucket_total{bucket="3_10"} 484
telemt_desync_frames_bucket_total{bucket="gt_10"} 433
telemt_pool_swap_total 11
telemt_pool_force_close_total 451
telemt_me_writer_removed_unexpected_total 7242
telemt_me_writer_restored_same_endpoint_total 7002
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 618124
telemt_user_connections_current{user="hello"} 858
telemt_user_octets_from_client{user="hello"} 6918406472 (6.44 GB)
telemt_user_octets_to_client{user="hello"} 185562129144 (172.82 GB)
telemt_user_unique_ips_current{user="hello"} 78
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 49247.9 (13h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 294983
telemt_connections_bad_total 2742
telemt_handshake_timeouts_total 26950
telemt_upstream_connect_attempt_total 95762
telemt_upstream_connect_success_total 94348
telemt_upstream_connect_fail_total 669
telemt_upstream_connect_attempts_per_request{bucket="1"} 94342
telemt_upstream_connect_attempts_per_request{bucket="2"} 675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 669
telemt_me_keepalive_timeout_total 1360
telemt_me_reconnect_attempts_total 54578
telemt_me_reconnect_success_total 54492
telemt_me_reader_eof_total 55893
telemt_me_idle_close_by_peer_total 55892
telemt_me_route_drop_no_conn_total 132089
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 209
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 583
telemt_desync_full_logged_total 205
telemt_desync_suppressed_total 378
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 212
telemt_pool_swap_total 3
telemt_pool_force_close_total 216
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 55973
telemt_me_writer_restored_same_endpoint_total 54467
telemt_me_writer_removed_unexpected_minus_restored_total 1506
telemt_user_connections_total{user="hello"} 230831
telemt_user_connections_current{user="hello"} 372
telemt_user_octets_from_client{user="hello"} 2741380204 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 76376736476 (71.13 GB)
telemt_user_unique_ips_current{user="hello"} 35
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 49246.8 (13h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 587971
telemt_connections_bad_total 148938
telemt_handshake_timeouts_total 17838
telemt_upstream_connect_attempt_total 73249
telemt_upstream_connect_success_total 72812
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 72811
telemt_upstream_connect_attempts_per_request{bucket="2"} 210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30026
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_timeout_total 946
telemt_me_reconnect_attempts_total 34018
telemt_me_reconnect_success_total 33932
telemt_me_reader_eof_total 35749
telemt_me_idle_close_by_peer_total 35745
telemt_me_route_drop_no_conn_total 214523
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 206
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1005
telemt_desync_full_logged_total 364
telemt_desync_suppressed_total 641
telemt_desync_frames_bucket_total{bucket="1_2"} 309
telemt_desync_frames_bucket_total{bucket="3_10"} 332
telemt_desync_frames_bucket_total{bucket="gt_10"} 364
telemt_pool_swap_total 4
telemt_pool_force_close_total 201
telemt_me_writer_removed_unexpected_total 35761
telemt_me_writer_restored_same_endpoint_total 33911
telemt_me_writer_removed_unexpected_minus_restored_total 1850
telemt_user_connections_total{user="hello"} 402607
telemt_user_connections_current{user="hello"} 599
telemt_user_octets_from_client{user="hello"} 5077426164 (4.73 GB)
telemt_user_octets_to_client{user="hello"} 138023966452 (128.54 GB)
telemt_user_unique_ips_current{user="hello"} 55
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 49245.8 (13h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 384869
telemt_connections_bad_total 26437
telemt_handshake_timeouts_total 66093
telemt_upstream_connect_attempt_total 35998
telemt_upstream_connect_success_total 35854
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 35854
telemt_upstream_connect_attempts_per_request{bucket="2"} 70
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13573
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 406
telemt_me_reconnect_attempts_total 7356
telemt_me_reconnect_success_total 7331
telemt_me_reader_eof_total 7475
telemt_me_idle_close_by_peer_total 7475
telemt_me_route_drop_no_conn_total 108158
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 203
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 210
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 13
telemt_pool_force_close_total 316
telemt_me_writer_removed_unexpected_total 7475
telemt_me_writer_restored_same_endpoint_total 7310
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 270522
telemt_user_connections_current{user="hello"} 429
telemt_user_octets_from_client{user="hello"} 2939499444 (2.74 GB)
telemt_user_octets_to_client{user="hello"} 97037994140 (90.37 GB)
telemt_user_unique_ips_current{user="hello"} 42
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 49244.5 (13h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 519630
telemt_connections_bad_total 6811
telemt_handshake_timeouts_total 132361
telemt_upstream_connect_attempt_total 70372
telemt_upstream_connect_success_total 69893
telemt_upstream_connect_fail_total 227
telemt_upstream_connect_attempts_per_request{bucket="1"} 69893
telemt_upstream_connect_attempts_per_request{bucket="2"} 227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27583
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 227
telemt_me_keepalive_timeout_total 915
telemt_me_reconnect_attempts_total 34039
telemt_me_reconnect_success_total 34007
telemt_me_reader_eof_total 35699
telemt_me_idle_close_by_peer_total 35698
telemt_me_route_drop_no_conn_total 162655
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 207
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 587
telemt_desync_full_logged_total 198
telemt_desync_suppressed_total 389
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 263
telemt_desync_frames_bucket_total{bucket="gt_10"} 205
telemt_pool_swap_total 6
telemt_pool_force_close_total 262
telemt_pool_stale_pick_total 2870
telemt_me_writer_removed_unexpected_total 35711
telemt_me_writer_restored_same_endpoint_total 33982
telemt_me_writer_removed_unexpected_minus_restored_total 1729
telemt_user_connections_total{user="hello"} 357655
telemt_user_connections_current{user="hello"} 520
telemt_user_octets_from_client{user="hello"} 4730241496 (4.41 GB)
telemt_user_octets_to_client{user="hello"} 94850834076 (88.34 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 47
```