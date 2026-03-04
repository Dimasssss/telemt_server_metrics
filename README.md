# Server Metrics 2026-03-04 08:17:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 40023.1 (11h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 461409
telemt_connections_bad_total 7986
telemt_handshake_timeouts_total 6418
telemt_upstream_connect_attempt_total 24721
telemt_upstream_connect_success_total 24608
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 24608
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10656
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 258
telemt_me_reconnect_attempts_total 4809
telemt_me_reconnect_success_total 4775
telemt_me_reader_eof_total 4887
telemt_me_idle_close_by_peer_total 4887
telemt_me_route_drop_no_conn_total 156106
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 160
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 882
telemt_desync_full_logged_total 323
telemt_desync_suppressed_total 559
telemt_desync_frames_bucket_total{bucket="1_2"} 259
telemt_desync_frames_bucket_total{bucket="3_10"} 326
telemt_desync_frames_bucket_total{bucket="gt_10"} 297
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 4887
telemt_me_writer_restored_same_endpoint_total 4754
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 388727
telemt_user_connections_current{user="hello"} 990
telemt_user_octets_from_client{user="hello"} 4489803656 (4.18 GB)
telemt_user_octets_to_client{user="hello"} 116141062492 (108.16 GB)
telemt_user_unique_ips_current{user="hello"} 91
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 40019.7 (11h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192581
telemt_connections_bad_total 1872
telemt_handshake_timeouts_total 23784
telemt_upstream_connect_attempt_total 81825
telemt_upstream_connect_success_total 80613
telemt_upstream_connect_fail_total 568
telemt_upstream_connect_attempts_per_request{bucket="1"} 80607
telemt_upstream_connect_attempts_per_request{bucket="2"} 574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25973
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 568
telemt_me_keepalive_timeout_total 1226
telemt_me_reconnect_attempts_total 47473
telemt_me_reconnect_success_total 47395
telemt_me_reader_eof_total 48582
telemt_me_idle_close_by_peer_total 48581
telemt_me_route_drop_no_conn_total 81595
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 173
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 414
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 268
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 191
telemt_desync_frames_bucket_total{bucket="gt_10"} 135
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 48662
telemt_me_writer_restored_same_endpoint_total 47370
telemt_me_writer_removed_unexpected_minus_restored_total 1292
telemt_user_connections_total{user="hello"} 139516
telemt_user_connections_current{user="hello"} 408
telemt_user_octets_from_client{user="hello"} 1670923376 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 53402167048 (49.73 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 40018.5 (11h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 393301
telemt_connections_bad_total 113639
telemt_handshake_timeouts_total 11175
telemt_upstream_connect_attempt_total 60146
telemt_upstream_connect_success_total 59786
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 59785
telemt_upstream_connect_attempts_per_request{bucket="2"} 172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25459
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_timeout_total 799
telemt_me_reconnect_attempts_total 27720
telemt_me_reconnect_success_total 27649
telemt_me_reader_eof_total 29194
telemt_me_idle_close_by_peer_total 29191
telemt_me_route_drop_no_conn_total 128223
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 170
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 614
telemt_desync_full_logged_total 231
telemt_desync_suppressed_total 383
telemt_desync_frames_bucket_total{bucket="1_2"} 173
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 220
telemt_pool_swap_total 4
telemt_pool_force_close_total 199
telemt_me_writer_removed_unexpected_total 29205
telemt_me_writer_restored_same_endpoint_total 27628
telemt_me_writer_removed_unexpected_minus_restored_total 1577
telemt_user_connections_total{user="hello"} 253614
telemt_user_connections_current{user="hello"} 509
telemt_user_octets_from_client{user="hello"} 2476620552 (2.31 GB)
telemt_user_octets_to_client{user="hello"} 95142055204 (88.61 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 40017.4 (11h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220950
telemt_connections_bad_total 18112
telemt_handshake_timeouts_total 7980
telemt_upstream_connect_attempt_total 30046
telemt_upstream_connect_success_total 29919
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 29919
telemt_upstream_connect_attempts_per_request{bucket="2"} 62
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11358
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 341
telemt_me_reconnect_attempts_total 6307
telemt_me_reconnect_success_total 6291
telemt_me_reader_eof_total 6410
telemt_me_idle_close_by_peer_total 6410
telemt_me_route_drop_no_conn_total 72167
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 167
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 11
telemt_pool_force_close_total 261
telemt_me_writer_removed_unexpected_total 6410
telemt_me_writer_restored_same_endpoint_total 6270
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 175775
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 1902515600 (1.77 GB)
telemt_user_octets_to_client{user="hello"} 62612416460 (58.31 GB)
telemt_user_unique_ips_current{user="hello"} 32
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 40016.2 (11h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371631
telemt_connections_bad_total 6442
telemt_handshake_timeouts_total 131724
telemt_upstream_connect_attempt_total 58897
telemt_upstream_connect_success_total 58498
telemt_upstream_connect_fail_total 187
telemt_upstream_connect_attempts_per_request{bucket="1"} 58498
telemt_upstream_connect_attempts_per_request{bucket="2"} 187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23309
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 187
telemt_me_keepalive_timeout_total 790
telemt_me_reconnect_attempts_total 27841
telemt_me_reconnect_success_total 27820
telemt_me_reader_eof_total 29251
telemt_me_idle_close_by_peer_total 29250
telemt_me_route_drop_no_conn_total 105888
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 171
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 250
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 165
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 122
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 4
telemt_pool_force_close_total 117
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 29265
telemt_me_writer_restored_same_endpoint_total 27795
telemt_me_writer_removed_unexpected_minus_restored_total 1470
telemt_user_connections_total{user="hello"} 224937
telemt_user_connections_current{user="hello"} 471
telemt_user_octets_from_client{user="hello"} 3037611952 (2.83 GB)
telemt_user_octets_to_client{user="hello"} 57285863224 (53.35 GB)
telemt_user_unique_ips_current{user="hello"} 51
```