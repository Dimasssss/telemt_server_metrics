# Server Metrics 2026-03-06 15:40:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 19112.1 (5h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 568974
telemt_connections_bad_total 5759
telemt_handshake_timeouts_total 2872
telemt_upstream_connect_attempt_total 9761
telemt_upstream_connect_success_total 9702
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 9726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4505
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 129
telemt_me_reconnect_attempts_total 1969
telemt_me_reconnect_success_total 1956
telemt_me_reader_eof_total 2054
telemt_me_idle_close_by_peer_total 2054
telemt_me_route_drop_no_conn_total 203798
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 77
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 3017
telemt_desync_full_logged_total 735
telemt_desync_suppressed_total 2282
telemt_desync_frames_bucket_total{bucket="1_2"} 721
telemt_desync_frames_bucket_total{bucket="3_10"} 1028
telemt_desync_frames_bucket_total{bucket="gt_10"} 1268
telemt_pool_swap_total 4
telemt_pool_force_close_total 233
telemt_me_writer_removed_unexpected_total 2056
telemt_me_writer_restored_same_endpoint_total 1950
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 484895
telemt_user_connections_current{user="hello"} 1153
telemt_user_octets_from_client{user="hello"} 11923207888 (11.10 GB)
telemt_user_octets_to_client{user="hello"} 188227017980 (175.30 GB)
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 302
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 19112.1 (5h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216175
telemt_connections_bad_total 861
telemt_handshake_timeouts_total 6640
telemt_upstream_connect_attempt_total 8997
telemt_upstream_connect_success_total 8976
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 8997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4677
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 113
telemt_me_reconnect_attempts_total 915
telemt_me_reconnect_success_total 900
telemt_me_reader_eof_total 950
telemt_me_idle_close_by_peer_total 950
telemt_me_route_drop_no_conn_total 107051
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 755
telemt_desync_full_logged_total 243
telemt_desync_suppressed_total 512
telemt_desync_frames_bucket_total{bucket="1_2"} 128
telemt_desync_frames_bucket_total{bucket="3_10"} 284
telemt_desync_frames_bucket_total{bucket="gt_10"} 343
telemt_pool_swap_total 5
telemt_pool_force_close_total 196
telemt_me_writer_removed_unexpected_total 950
telemt_me_writer_restored_same_endpoint_total 900
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 199415
telemt_user_connections_current{user="hello"} 474
telemt_user_octets_from_client{user="hello"} 2236437960 (2.08 GB)
telemt_user_octets_to_client{user="hello"} 83593581528 (77.85 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 19111.9 (5h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 430050
telemt_connections_bad_total 5300
telemt_handshake_timeouts_total 38935
telemt_upstream_connect_attempt_total 15823
telemt_upstream_connect_success_total 15748
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 15811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7071
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 212
telemt_me_reconnect_attempts_total 5342
telemt_me_reconnect_success_total 5321
telemt_me_reader_eof_total 5636
telemt_me_idle_close_by_peer_total 5636
telemt_me_route_drop_no_conn_total 203701
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 78
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 831
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 582
telemt_desync_frames_bucket_total{bucket="1_2"} 194
telemt_desync_frames_bucket_total{bucket="3_10"} 325
telemt_desync_frames_bucket_total{bucket="gt_10"} 312
telemt_pool_swap_total 2
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 5640
telemt_me_writer_restored_same_endpoint_total 5316
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 372249
telemt_user_connections_current{user="hello"} 709
telemt_user_octets_from_client{user="hello"} 5633321212 (5.25 GB)
telemt_user_octets_to_client{user="hello"} 119057382448 (110.88 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 18428.1 (5h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 340771
telemt_connections_bad_total 81550
telemt_handshake_timeouts_total 10371
telemt_upstream_connect_attempt_total 9852
telemt_upstream_connect_success_total 9851
telemt_upstream_connect_attempts_per_request{bucket="1"} 9851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5911
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3940
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 1941
telemt_me_reconnect_success_total 1925
telemt_me_reader_eof_total 1964
telemt_me_idle_close_by_peer_total 1964
telemt_me_route_drop_no_conn_total 109918
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 79
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 290
telemt_desync_full_logged_total 103
telemt_desync_suppressed_total 187
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 100
telemt_desync_frames_bucket_total{bucket="gt_10"} 111
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 1964
telemt_me_writer_restored_same_endpoint_total 1925
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 214339
telemt_user_connections_current{user="hello"} 517
telemt_user_octets_from_client{user="hello"} 2526954016 (2.35 GB)
telemt_user_octets_to_client{user="hello"} 78337347200 (72.96 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 19112.4 (5h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 337881
telemt_connections_bad_total 10808
telemt_handshake_timeouts_total 2760
telemt_upstream_connect_attempt_total 9356
telemt_upstream_connect_success_total 9344
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9345
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4219
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 152
telemt_me_reconnect_attempts_total 1761
telemt_me_reconnect_success_total 1746
telemt_me_reader_eof_total 1841
telemt_me_idle_close_by_peer_total 1840
telemt_me_route_drop_no_conn_total 173611
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 628
telemt_desync_full_logged_total 220
telemt_desync_suppressed_total 408
telemt_desync_frames_bucket_total{bucket="1_2"} 284
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 158
telemt_pool_swap_total 5
telemt_pool_force_close_total 221
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1845
telemt_me_writer_restored_same_endpoint_total 1744
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 309992
telemt_user_connections_current{user="hello"} 563
telemt_user_octets_from_client{user="hello"} 14923574500 (13.90 GB)
telemt_user_octets_to_client{user="hello"} 166789946072 (155.34 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 180
```