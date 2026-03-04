# Server Metrics 2026-03-04 15:38:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 66470.8 (18h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1251099
telemt_connections_bad_total 16347
telemt_handshake_timeouts_total 22375
telemt_upstream_connect_attempt_total 38598
telemt_upstream_connect_success_total 38423
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 38423
telemt_upstream_connect_attempts_per_request{bucket="2"} 68
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17207
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 44
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 443
telemt_me_reconnect_attempts_total 8207
telemt_me_reconnect_success_total 8144
telemt_me_reader_eof_total 8410
telemt_me_idle_close_by_peer_total 8409
telemt_me_route_drop_no_conn_total 461101
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 259
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2502
telemt_desync_full_logged_total 807
telemt_desync_suppressed_total 1695
telemt_desync_frames_bucket_total{bucket="1_2"} 734
telemt_desync_frames_bucket_total{bucket="3_10"} 937
telemt_desync_frames_bucket_total{bucket="gt_10"} 831
telemt_pool_swap_total 17
telemt_pool_force_close_total 715
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8410
telemt_me_writer_restored_same_endpoint_total 8122
telemt_me_writer_removed_unexpected_minus_restored_total 288
telemt_user_connections_total{user="hello"} 1010553
telemt_user_connections_current{user="hello"} 1133
telemt_user_octets_from_client{user="hello"} 13436884876 (12.51 GB)
telemt_user_octets_to_client{user="hello"} 341236126360 (317.80 GB)
telemt_user_unique_ips_current{user="hello"} 90
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 66467.3 (18h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 474941
telemt_connections_bad_total 4163
telemt_handshake_timeouts_total 30477
telemt_upstream_connect_attempt_total 120938
telemt_upstream_connect_success_total 119220
telemt_upstream_connect_fail_total 821
telemt_upstream_connect_attempts_per_request{bucket="1"} 119214
telemt_upstream_connect_attempts_per_request{bucket="2"} 827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 77417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41779
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 821
telemt_me_keepalive_timeout_total 1584
telemt_me_reconnect_attempts_total 66093
telemt_me_reconnect_success_total 65988
telemt_me_reader_eof_total 67698
telemt_me_idle_close_by_peer_total 67697
telemt_me_route_drop_no_conn_total 192878
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 278
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1162
telemt_desync_full_logged_total 351
telemt_desync_suppressed_total 811
telemt_desync_frames_bucket_total{bucket="1_2"} 216
telemt_desync_frames_bucket_total{bucket="3_10"} 457
telemt_desync_frames_bucket_total{bucket="gt_10"} 489
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 67778
telemt_me_writer_restored_same_endpoint_total 65963
telemt_me_writer_removed_unexpected_minus_restored_total 1815
telemt_user_connections_total{user="hello"} 376905
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 5835828776 (5.44 GB)
telemt_user_octets_to_client{user="hello"} 119663596028 (111.45 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 66466.0 (18h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 961387
telemt_connections_bad_total 196924
telemt_handshake_timeouts_total 30167
telemt_upstream_connect_attempt_total 88073
telemt_upstream_connect_success_total 87489
telemt_upstream_connect_fail_total 282
telemt_upstream_connect_attempts_per_request{bucket="1"} 87488
telemt_upstream_connect_attempts_per_request{bucket="2"} 283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51712
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35546
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 231
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 282
telemt_me_keepalive_timeout_total 1144
telemt_me_reconnect_attempts_total 39393
telemt_me_reconnect_success_total 39290
telemt_me_reader_eof_total 41354
telemt_me_idle_close_by_peer_total 41349
telemt_me_route_drop_no_conn_total 349030
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_single_endpoint_shadow_rotate_total 273
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2021
telemt_desync_full_logged_total 671
telemt_desync_suppressed_total 1350
telemt_desync_frames_bucket_total{bucket="1_2"} 619
telemt_desync_frames_bucket_total{bucket="3_10"} 651
telemt_desync_frames_bucket_total{bucket="gt_10"} 751
telemt_pool_swap_total 7
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 41366
telemt_me_writer_restored_same_endpoint_total 39268
telemt_me_writer_removed_unexpected_minus_restored_total 2098
telemt_user_connections_total{user="hello"} 688660
telemt_user_connections_current{user="hello"} 640
telemt_user_octets_from_client{user="hello"} 13937420536 (12.98 GB)
telemt_user_octets_to_client{user="hello"} 233058377976 (217.05 GB)
telemt_user_unique_ips_current{user="hello"} 66
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 13143.3 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207103
telemt_connections_bad_total 22216
telemt_handshake_timeouts_total 6021
telemt_upstream_connect_attempt_total 5397
telemt_upstream_connect_success_total 5397
telemt_upstream_connect_attempts_per_request{bucket="1"} 5397
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2219
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 858
telemt_me_reconnect_success_total 869
telemt_me_reader_eof_total 877
telemt_me_idle_close_by_peer_total 877
telemt_me_route_drop_no_conn_total 63255
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 217
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 136
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 4
telemt_pool_force_close_total 146
telemt_me_writer_removed_unexpected_total 877
telemt_me_writer_restored_same_endpoint_total 848
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 171676
telemt_user_connections_current{user="hello"} 473
telemt_user_octets_from_client{user="hello"} 2124773416 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 69448539304 (64.68 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 13502.7 (3h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233523
telemt_connections_bad_total 2507
telemt_handshake_timeouts_total 3580
telemt_upstream_connect_attempt_total 6915
telemt_upstream_connect_success_total 6884
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 6884
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2882
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 1291
telemt_me_reconnect_success_total 1298
telemt_me_reader_eof_total 1324
telemt_me_idle_close_by_peer_total 1324
telemt_me_route_drop_no_conn_total 86946
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 514
telemt_desync_full_logged_total 197
telemt_desync_suppressed_total 317
telemt_desync_frames_bucket_total{bucket="1_2"} 76
telemt_desync_frames_bucket_total{bucket="3_10"} 220
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 3
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 1324
telemt_me_writer_restored_same_endpoint_total 1278
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 199099
telemt_user_connections_current{user="hello"} 645
telemt_user_octets_from_client{user="hello"} 3211294316 (2.99 GB)
telemt_user_octets_to_client{user="hello"} 57974998956 (53.99 GB)
telemt_user_unique_ips_current{user="hello"} 56
```