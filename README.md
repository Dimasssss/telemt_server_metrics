# Server Metrics 2026-03-04 15:23:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 65548.3 (18h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1226599
telemt_connections_bad_total 15125
telemt_handshake_timeouts_total 22205
telemt_upstream_connect_attempt_total 38141
telemt_upstream_connect_success_total 37974
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 37974
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17016
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 437
telemt_me_reconnect_attempts_total 8187
telemt_me_reconnect_success_total 8125
telemt_me_reader_eof_total 8390
telemt_me_idle_close_by_peer_total 8389
telemt_me_route_drop_no_conn_total 451906
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 256
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2413
telemt_desync_full_logged_total 784
telemt_desync_suppressed_total 1629
telemt_desync_frames_bucket_total{bucket="1_2"} 725
telemt_desync_frames_bucket_total{bucket="3_10"} 900
telemt_desync_frames_bucket_total{bucket="gt_10"} 788
telemt_pool_swap_total 17
telemt_pool_force_close_total 715
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8390
telemt_me_writer_restored_same_endpoint_total 8103
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 988443
telemt_user_connections_current{user="hello"} 1058
telemt_user_octets_from_client{user="hello"} 13189758248 (12.28 GB)
telemt_user_octets_to_client{user="hello"} 333121665364 (310.24 GB)
telemt_user_unique_ips_current{user="hello"} 106
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 65544.8 (18h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 465471
telemt_connections_bad_total 3842
telemt_handshake_timeouts_total 30419
telemt_upstream_connect_attempt_total 118965
telemt_upstream_connect_success_total 117255
telemt_upstream_connect_fail_total 817
telemt_upstream_connect_attempts_per_request{bucket="1"} 117249
telemt_upstream_connect_attempts_per_request{bucket="2"} 823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40997
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 817
telemt_me_keepalive_timeout_total 1564
telemt_me_reconnect_attempts_total 65021
telemt_me_reconnect_success_total 64918
telemt_me_reader_eof_total 66602
telemt_me_idle_close_by_peer_total 66601
telemt_me_route_drop_no_conn_total 189716
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 274
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1107
telemt_desync_full_logged_total 336
telemt_desync_suppressed_total 771
telemt_desync_frames_bucket_total{bucket="1_2"} 211
telemt_desync_frames_bucket_total{bucket="3_10"} 447
telemt_desync_frames_bucket_total{bucket="gt_10"} 449
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 66682
telemt_me_writer_restored_same_endpoint_total 64893
telemt_me_writer_removed_unexpected_minus_restored_total 1789
telemt_user_connections_total{user="hello"} 368111
telemt_user_connections_current{user="hello"} 491
telemt_user_octets_from_client{user="hello"} 5759906700 (5.36 GB)
telemt_user_octets_to_client{user="hello"} 116632544064 (108.62 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 65543.5 (18h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 940335
telemt_connections_bad_total 194311
telemt_handshake_timeouts_total 29912
telemt_upstream_connect_attempt_total 86960
telemt_upstream_connect_success_total 86378
telemt_upstream_connect_fail_total 281
telemt_upstream_connect_attempts_per_request{bucket="1"} 86377
telemt_upstream_connect_attempts_per_request{bucket="2"} 282
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51151
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34999
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 281
telemt_me_keepalive_timeout_total 1126
telemt_me_reconnect_attempts_total 38973
telemt_me_reconnect_success_total 38871
telemt_me_reader_eof_total 40898
telemt_me_idle_close_by_peer_total 40893
telemt_me_route_drop_no_conn_total 340897
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_single_endpoint_shadow_rotate_total 270
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1988
telemt_desync_full_logged_total 658
telemt_desync_suppressed_total 1330
telemt_desync_frames_bucket_total{bucket="1_2"} 606
telemt_desync_frames_bucket_total{bucket="3_10"} 642
telemt_desync_frames_bucket_total{bucket="gt_10"} 740
telemt_pool_swap_total 7
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 40910
telemt_me_writer_restored_same_endpoint_total 38849
telemt_me_writer_removed_unexpected_minus_restored_total 2061
telemt_user_connections_total{user="hello"} 670906
telemt_user_connections_current{user="hello"} 726
telemt_user_octets_from_client{user="hello"} 13781334268 (12.83 GB)
telemt_user_octets_to_client{user="hello"} 227897259252 (212.25 GB)
telemt_user_unique_ips_current{user="hello"} 76
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 12220.8 (3h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184216
telemt_connections_bad_total 17107
telemt_handshake_timeouts_total 5604
telemt_upstream_connect_attempt_total 5261
telemt_upstream_connect_success_total 5261
telemt_upstream_connect_attempts_per_request{bucket="1"} 5261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2145
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 858
telemt_me_reconnect_success_total 869
telemt_me_reader_eof_total 877
telemt_me_idle_close_by_peer_total 877
telemt_me_route_drop_no_conn_total 58827
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 203
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 127
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_pool_swap_total 4
telemt_pool_force_close_total 146
telemt_me_writer_removed_unexpected_total 877
telemt_me_writer_restored_same_endpoint_total 848
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 155200
telemt_user_connections_current{user="hello"} 481
telemt_user_octets_from_client{user="hello"} 1977853064 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 67071370776 (62.47 GB)
telemt_user_unique_ips_current{user="hello"} 48
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 12580.4 (3h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213048
telemt_connections_bad_total 1959
telemt_handshake_timeouts_total 3385
telemt_upstream_connect_attempt_total 6584
telemt_upstream_connect_success_total 6553
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 6553
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2742
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 93
telemt_me_reconnect_attempts_total 1284
telemt_me_reconnect_success_total 1292
telemt_me_reader_eof_total 1318
telemt_me_idle_close_by_peer_total 1318
telemt_me_route_drop_no_conn_total 80648
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 503
telemt_desync_full_logged_total 193
telemt_desync_suppressed_total 310
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 215
telemt_pool_swap_total 3
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 1318
telemt_me_writer_restored_same_endpoint_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 185541
telemt_user_connections_current{user="hello"} 589
telemt_user_octets_from_client{user="hello"} 3011598360 (2.80 GB)
telemt_user_octets_to_client{user="hello"} 52099592124 (48.52 GB)
telemt_user_unique_ips_current{user="hello"} 46
```