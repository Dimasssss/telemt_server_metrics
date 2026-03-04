# Server Metrics 2026-03-04 15:17:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 65241.2 (18h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1219099
telemt_connections_bad_total 14844
telemt_handshake_timeouts_total 22106
telemt_upstream_connect_attempt_total 38007
telemt_upstream_connect_success_total 37840
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 37840
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16957
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 435
telemt_me_reconnect_attempts_total 8183
telemt_me_reconnect_success_total 8121
telemt_me_reader_eof_total 8386
telemt_me_idle_close_by_peer_total 8385
telemt_me_route_drop_no_conn_total 449248
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 256
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2386
telemt_desync_full_logged_total 775
telemt_desync_suppressed_total 1611
telemt_desync_frames_bucket_total{bucket="1_2"} 716
telemt_desync_frames_bucket_total{bucket="3_10"} 894
telemt_desync_frames_bucket_total{bucket="gt_10"} 776
telemt_pool_swap_total 17
telemt_pool_force_close_total 715
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8386
telemt_me_writer_restored_same_endpoint_total 8099
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 981788
telemt_user_connections_current{user="hello"} 1143
telemt_user_octets_from_client{user="hello"} 13112067160 (12.21 GB)
telemt_user_octets_to_client{user="hello"} 330848601856 (308.13 GB)
telemt_user_unique_ips_current{user="hello"} 110
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 65237.6 (18h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 462557
telemt_connections_bad_total 3827
telemt_handshake_timeouts_total 30354
telemt_upstream_connect_attempt_total 118295
telemt_upstream_connect_success_total 116585
telemt_upstream_connect_fail_total 817
telemt_upstream_connect_attempts_per_request{bucket="1"} 116579
telemt_upstream_connect_attempts_per_request{bucket="2"} 823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 75824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40737
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 817
telemt_me_keepalive_timeout_total 1556
telemt_me_reconnect_attempts_total 64633
telemt_me_reconnect_success_total 64531
telemt_me_reader_eof_total 66199
telemt_me_idle_close_by_peer_total 66198
telemt_me_route_drop_no_conn_total 188562
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 274
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1081
telemt_desync_full_logged_total 328
telemt_desync_suppressed_total 753
telemt_desync_frames_bucket_total{bucket="1_2"} 204
telemt_desync_frames_bucket_total{bucket="3_10"} 439
telemt_desync_frames_bucket_total{bucket="gt_10"} 438
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 66279
telemt_me_writer_restored_same_endpoint_total 64506
telemt_me_writer_removed_unexpected_minus_restored_total 1773
telemt_user_connections_total{user="hello"} 365298
telemt_user_connections_current{user="hello"} 458
telemt_user_octets_from_client{user="hello"} 5739450760 (5.35 GB)
telemt_user_octets_to_client{user="hello"} 116021826688 (108.05 GB)
telemt_user_unique_ips_current{user="hello"} 51
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 65236.4 (18h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 933924
telemt_connections_bad_total 193452
telemt_handshake_timeouts_total 29902
telemt_upstream_connect_attempt_total 86535
telemt_upstream_connect_success_total 85953
telemt_upstream_connect_fail_total 281
telemt_upstream_connect_attempts_per_request{bucket="1"} 85952
telemt_upstream_connect_attempts_per_request{bucket="2"} 282
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50893
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34832
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 281
telemt_me_keepalive_timeout_total 1120
telemt_me_reconnect_attempts_total 38773
telemt_me_reconnect_success_total 38671
telemt_me_reader_eof_total 40693
telemt_me_idle_close_by_peer_total 40689
telemt_me_route_drop_no_conn_total 338914
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_single_endpoint_shadow_rotate_total 270
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1985
telemt_desync_full_logged_total 657
telemt_desync_suppressed_total 1328
telemt_desync_frames_bucket_total{bucket="1_2"} 605
telemt_desync_frames_bucket_total{bucket="3_10"} 641
telemt_desync_frames_bucket_total{bucket="gt_10"} 739
telemt_pool_swap_total 7
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 40705
telemt_me_writer_restored_same_endpoint_total 38649
telemt_me_writer_removed_unexpected_minus_restored_total 2056
telemt_user_connections_total{user="hello"} 665485
telemt_user_connections_current{user="hello"} 701
telemt_user_octets_from_client{user="hello"} 13743271000 (12.80 GB)
telemt_user_octets_to_client{user="hello"} 226335913332 (210.79 GB)
telemt_user_unique_ips_current{user="hello"} 58
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 11913.6 (3h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177756
telemt_connections_bad_total 16830
telemt_handshake_timeouts_total 5342
telemt_upstream_connect_attempt_total 5259
telemt_upstream_connect_success_total 5259
telemt_upstream_connect_attempts_per_request{bucket="1"} 5259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2143
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 858
telemt_me_reconnect_success_total 869
telemt_me_reader_eof_total 877
telemt_me_idle_close_by_peer_total 877
telemt_me_route_drop_no_conn_total 57499
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 199
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 4
telemt_pool_force_close_total 146
telemt_me_writer_removed_unexpected_total 877
telemt_me_writer_restored_same_endpoint_total 848
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 149551
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 1941996752 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 66023742444 (61.49 GB)
telemt_user_unique_ips_current{user="hello"} 66
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 12273.2 (3h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208295
telemt_connections_bad_total 1859
telemt_handshake_timeouts_total 3345
telemt_upstream_connect_attempt_total 6524
telemt_upstream_connect_success_total 6493
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 6493
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2706
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 93
telemt_me_reconnect_attempts_total 1284
telemt_me_reconnect_success_total 1292
telemt_me_reader_eof_total 1318
telemt_me_idle_close_by_peer_total 1318
telemt_me_route_drop_no_conn_total 78601
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 495
telemt_desync_full_logged_total 190
telemt_desync_suppressed_total 305
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 210
telemt_desync_frames_bucket_total{bucket="gt_10"} 214
telemt_pool_swap_total 3
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 1318
telemt_me_writer_restored_same_endpoint_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 181215
telemt_user_connections_current{user="hello"} 631
telemt_user_octets_from_client{user="hello"} 2984937412 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 50869971556 (47.38 GB)
telemt_user_unique_ips_current{user="hello"} 61
```