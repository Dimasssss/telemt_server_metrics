# Server Metrics 2026-03-05 00:22:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 12541.3 (3h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104064
telemt_connections_bad_total 1401
telemt_handshake_timeouts_total 765
telemt_upstream_connect_attempt_total 17251
telemt_upstream_connect_success_total 17087
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 17086
telemt_upstream_connect_attempts_per_request{bucket="2"} 52
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6023
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 548
telemt_me_reconnect_attempts_total 8055
telemt_me_reconnect_success_total 8048
telemt_me_reader_eof_total 8331
telemt_me_idle_close_by_peer_total 8330
telemt_me_route_drop_no_conn_total 27918
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 134
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 54
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 69
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_me_writer_removed_unexpected_total 8390
telemt_me_writer_restored_same_endpoint_total 8028
telemt_me_writer_removed_unexpected_minus_restored_total 362
telemt_user_connections_total{user="hello"} 90733
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 2885008048 (2.69 GB)
telemt_user_octets_to_client{user="hello"} 49417160612 (46.02 GB)
telemt_user_unique_ips_current{user="hello"} 37
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 12536.2 (3h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40435
telemt_connections_bad_total 784
telemt_handshake_timeouts_total 924
telemt_upstream_connect_attempt_total 13472
telemt_upstream_connect_success_total 13166
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 13156
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4374
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 1022
telemt_me_reconnect_attempts_total 5116
telemt_me_reconnect_success_total 5090
telemt_me_reader_eof_total 5161
telemt_me_idle_close_by_peer_total 5160
telemt_me_route_drop_no_conn_total 12438
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 138
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_removed_unexpected_total 5265
telemt_me_writer_restored_same_endpoint_total 5065
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 36522
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 330698232 (315.38 MB)
telemt_user_octets_to_client{user="hello"} 10233416696 (9.53 GB)
telemt_user_unique_ips_current{user="hello"} 13
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 12532.7 (3h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94045
telemt_connections_bad_total 1310
telemt_handshake_timeouts_total 695
telemt_upstream_connect_attempt_total 5415
telemt_upstream_connect_success_total 5361
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 5361
telemt_upstream_connect_attempts_per_request{bucket="2"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2791
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 54
telemt_me_reconnect_attempts_total 271
telemt_me_reconnect_success_total 281
telemt_me_reader_eof_total 270
telemt_me_idle_close_by_peer_total 270
telemt_me_route_drop_no_conn_total 26754
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 172
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_pool_swap_total 4
telemt_pool_force_close_total 98
telemt_me_writer_removed_unexpected_total 270
telemt_me_writer_restored_same_endpoint_total 261
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 86309
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 1042631448 (994.33 MB)
telemt_user_octets_to_client{user="hello"} 29590962820 (27.56 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 44581.0 (12h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 551333
telemt_connections_bad_total 80215
telemt_handshake_timeouts_total 14738
telemt_upstream_connect_attempt_total 20450
telemt_upstream_connect_success_total 20448
telemt_upstream_connect_attempts_per_request{bucket="1"} 20448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8641
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 255
telemt_me_reconnect_attempts_total 2879
telemt_me_reconnect_success_total 2861
telemt_me_reader_eof_total 2917
telemt_me_idle_close_by_peer_total 2917
telemt_me_route_drop_no_conn_total 185867
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 182
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 720
telemt_desync_full_logged_total 303
telemt_desync_suppressed_total 417
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 291
telemt_pool_swap_total 17
telemt_pool_force_close_total 484
telemt_pool_stale_pick_total 22
telemt_me_writer_removed_unexpected_total 2918
telemt_me_writer_restored_same_endpoint_total 2834
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 427873
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 5847108044 (5.45 GB)
telemt_user_octets_to_client{user="hello"} 159717485316 (148.75 GB)
telemt_user_unique_ips_current{user="hello"} 18
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 44940.3 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 536921
telemt_connections_bad_total 3855
telemt_handshake_timeouts_total 5911
telemt_upstream_connect_attempt_total 28983
telemt_upstream_connect_success_total 28828
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 28828
telemt_upstream_connect_attempts_per_request{bucket="2"} 61
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11978
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 435
telemt_me_reconnect_attempts_total 6532
telemt_me_reconnect_success_total 6511
telemt_me_reader_eof_total 6755
telemt_me_idle_close_by_peer_total 6754
telemt_me_route_drop_no_conn_total 236368
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 180
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 831
telemt_desync_full_logged_total 302
telemt_desync_suppressed_total 529
telemt_desync_frames_bucket_total{bucket="1_2"} 170
telemt_desync_frames_bucket_total{bucket="3_10"} 351
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 10
telemt_pool_force_close_total 420
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 6760
telemt_me_writer_restored_same_endpoint_total 6489
telemt_me_writer_removed_unexpected_minus_restored_total 271
telemt_user_connections_total{user="hello"} 486375
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 7379189008 (6.87 GB)
telemt_user_octets_to_client{user="hello"} 162614888932 (151.45 GB)
telemt_user_unique_ips_current{user="hello"} 27
```