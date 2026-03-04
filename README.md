# Server Metrics 2026-03-04 09:55:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 45865.6 (12h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 644384
telemt_connections_bad_total 10946
telemt_handshake_timeouts_total 7373
telemt_upstream_connect_attempt_total 30644
telemt_upstream_connect_success_total 30516
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 30516
telemt_upstream_connect_attempts_per_request{bucket="2"} 54
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13564
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 6978
telemt_me_reconnect_success_total 6934
telemt_me_reader_eof_total 7151
telemt_me_idle_close_by_peer_total 7151
telemt_me_route_drop_no_conn_total 230038
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 183
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1096
telemt_desync_full_logged_total 386
telemt_desync_suppressed_total 710
telemt_desync_frames_bucket_total{bucket="1_2"} 309
telemt_desync_frames_bucket_total{bucket="3_10"} 414
telemt_desync_frames_bucket_total{bucket="gt_10"} 373
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 7151
telemt_me_writer_restored_same_endpoint_total 6913
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 529921
telemt_user_connections_current{user="hello"} 1063
telemt_user_octets_from_client{user="hello"} 5857488248 (5.46 GB)
telemt_user_octets_to_client{user="hello"} 156257213272 (145.53 GB)
telemt_user_unique_ips_current{user="hello"} 93
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 45862.1 (12h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257698
telemt_connections_bad_total 2097
telemt_handshake_timeouts_total 25886
telemt_upstream_connect_attempt_total 93716
telemt_upstream_connect_success_total 92412
telemt_upstream_connect_fail_total 614
telemt_upstream_connect_attempts_per_request{bucket="1"} 92406
telemt_upstream_connect_attempts_per_request{bucket="2"} 620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30324
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 614
telemt_me_keepalive_timeout_total 1343
telemt_me_reconnect_attempts_total 54316
telemt_me_reconnect_success_total 54234
telemt_me_reader_eof_total 55632
telemt_me_idle_close_by_peer_total 55631
telemt_me_route_drop_no_conn_total 119475
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 194
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 525
telemt_desync_full_logged_total 190
telemt_desync_suppressed_total 335
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 235
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 3
telemt_pool_force_close_total 216
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 55712
telemt_me_writer_restored_same_endpoint_total 54209
telemt_me_writer_removed_unexpected_minus_restored_total 1503
telemt_user_connections_total{user="hello"} 196533
telemt_user_connections_current{user="hello"} 433
telemt_user_octets_from_client{user="hello"} 2165070364 (2.02 GB)
telemt_user_octets_to_client{user="hello"} 66655803276 (62.08 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 45860.8 (12h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 522169
telemt_connections_bad_total 140225
telemt_handshake_timeouts_total 15824
telemt_upstream_connect_attempt_total 66011
telemt_upstream_connect_success_total 65604
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 65603
telemt_upstream_connect_attempts_per_request{bucket="2"} 195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27370
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 185
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_keepalive_timeout_total 874
telemt_me_reconnect_attempts_total 29837
telemt_me_reconnect_success_total 29757
telemt_me_reader_eof_total 31375
telemt_me_idle_close_by_peer_total 31372
telemt_me_route_drop_no_conn_total 177199
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 192
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 842
telemt_desync_full_logged_total 308
telemt_desync_suppressed_total 534
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 288
telemt_desync_frames_bucket_total{bucket="gt_10"} 304
telemt_pool_swap_total 4
telemt_pool_force_close_total 201
telemt_me_writer_removed_unexpected_total 31386
telemt_me_writer_restored_same_endpoint_total 29736
telemt_me_writer_removed_unexpected_minus_restored_total 1650
telemt_user_connections_total{user="hello"} 349969
telemt_user_connections_current{user="hello"} 715
telemt_user_octets_from_client{user="hello"} 3725893200 (3.47 GB)
telemt_user_octets_to_client{user="hello"} 124055259556 (115.54 GB)
telemt_user_unique_ips_current{user="hello"} 80
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 45859.8 (12h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 336163
telemt_connections_bad_total 23370
telemt_handshake_timeouts_total 53375
telemt_upstream_connect_attempt_total 32982
telemt_upstream_connect_success_total 32847
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 32847
telemt_upstream_connect_attempts_per_request{bucket="2"} 66
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12385
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 376
telemt_me_reconnect_attempts_total 6604
telemt_me_reconnect_success_total 6582
telemt_me_reader_eof_total 6707
telemt_me_idle_close_by_peer_total 6707
telemt_me_route_drop_no_conn_total 95661
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 188
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 173
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 98
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 13
telemt_pool_force_close_total 315
telemt_me_writer_removed_unexpected_total 6707
telemt_me_writer_restored_same_endpoint_total 6561
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 238140
telemt_user_connections_current{user="hello"} 370
telemt_user_octets_from_client{user="hello"} 2621036784 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 82305578116 (76.65 GB)
telemt_user_unique_ips_current{user="hello"} 38
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 45858.5 (12h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 467453
telemt_connections_bad_total 6489
telemt_handshake_timeouts_total 132158
telemt_upstream_connect_attempt_total 68199
telemt_upstream_connect_success_total 67774
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 67774
telemt_upstream_connect_attempts_per_request{bucket="2"} 200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26906
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_keepalive_timeout_total 897
telemt_me_reconnect_attempts_total 33514
telemt_me_reconnect_success_total 33484
telemt_me_reader_eof_total 35162
telemt_me_idle_close_by_peer_total 35161
telemt_me_route_drop_no_conn_total 143612
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 191
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 460
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 218
telemt_desync_frames_bucket_total{bucket="gt_10"} 150
telemt_pool_swap_total 6
telemt_pool_force_close_total 262
telemt_pool_stale_pick_total 2870
telemt_me_writer_removed_unexpected_total 35174
telemt_me_writer_restored_same_endpoint_total 33459
telemt_me_writer_removed_unexpected_minus_restored_total 1715
telemt_user_connections_total{user="hello"} 308960
telemt_user_connections_current{user="hello"} 610
telemt_user_octets_from_client{user="hello"} 4317583680 (4.02 GB)
telemt_user_octets_to_client{user="hello"} 77432635600 (72.11 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 56
```